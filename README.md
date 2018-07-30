#### 1、下拉刷新时的loading动画三个小圆点不显示的问题![image](https://github.com/zaishuiyixia/WeChat-small-program/raw/master/images/circle.png)

三个小圆点是小程序自带的。其实那三个点一直都是存在的，但是，由于那三个点的默认颜色为白色，而当前背景颜色也是白色，那么，就导致了，看不到那三个点了。

解决方法：

1. 修改背景颜色。在app.wxss中为page添加背景色。

2. 修改下拉刷新小圆点的默认颜色。在添加下拉刷新页面对应的json文件中添加。
