# 基于TVBOX二次开发
### 配置：
gradle:gradle-7.5-bin.zip
JDK:17
## Task：
1.视频手机竖屏，优化竖屏UI

#### 进度
优化竖屏UI：
1.在Androidmanifest.xml里面把方向都强制改成竖屏 V
2.优化竖屏UI
    2.1 把TVRecyclerView 换成RecyclerView V
    2.2 改变 RecyclerView 的item的宽高适配手机 V
        发现是有item的但是不知道是怎么联系起来的，而且只改了首页的item(mItemFrame)
待续。。。。。。。
这样绑定的：rvHotListForGrid.setAdapter(homeHotVodAdapter);
