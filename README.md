# awesome flutter

[Flutter Widget 分类](https://flutter.dev/docs/development/ui/widgets)

Flutter 项目开发中常用的 Widget 一些基础功能，由于每个 Widget 都有很多的属性，这里只列出了基本也是最常用的属性，更多的用法可以看 Widget 中每个属性的注释。我会持续更新这个 demo 集合，同时后续会增加更多自定义的 Widget。

## DemoContainer

Flutter 中最常用的 Widget 之一，可以设置 margin，padding，decoration，等设置复杂效果。

![DemoContainer](./img/DemoContainer.gif)

## DemoButton

常用的几种 Button

RaisedButton:Material Design 风格的 Button

FlatButton:扁平化的 Button

OutlineButton:带边框的 Button

IconButton:带 icon 的 Button

![DemoButton](./img/DemoButton.gif)

## DemoClipRRect

使用 ClipRRect 设置圆角。给 Container 设置 BoxDecoration 如果 child 是图片的话圆角是无效的，可以使用 ClipRRect 给图片或者复杂的 Widget 设置圆角。

![DemoClipRRect](./img/DemoClipRRect.gif)

## DemoColumn

列布局，继承自 Flex 可以对主轴和交叉轴进行设置来调整 Column 内的布局方式。

![DemoColumn](./img/DemoColumn.gif)

## DemoRow

行布局，和列布局类似，继承自 Flex 可以对主轴和交叉轴进行设置来调整 Row 内的布局方式。

![DemoRow](./img/DemoRow.gif)

## DemoExpanded

Expanded 必须方法 Flex 中，它会把 Flex 剩余的控件撑满，同时还可以给 Expanded 设置撑开的比例。

![DemoExpanded](./img/DemoExpanded.gif)

## DemoStack

栈布局，就像栈一样一层一层网上叠加，类似于 Android 里的 FrameLayout。可以通过 Positioned Widget 设置子 Widget 的位置。

![DemoStack](./img/DemoStack.gif)

## DemoVisibility

控制 Widget 的隐藏和显示。

![DemoVisibility](./img/DemoVisibility.gif)

## DemoOffstage

和 Visibility 类似控制 Widget 的隐藏和显示，比 Visibility 拥有更多的属性，可以在 Widget 隐藏之后不占用屏幕空间。

![DemoOffstage](./img/DemoOffstage.gif)

## DemoSafeArea

安全区域，加上之后会自动适配 Android 或者 iOS 的刘海屏。

![DemoSafeArea](./img/DemoSafeArea.gif)

## DemoPopMenuButton

弹出选择 Widget，有时候并不能完全满足我们的需求。

![DemoPopMenuButton](./img/DemoPopMenuButton.gif)

## DemoBottomSheet

底部弹出 Widget。

![DemoBottomSheet](./img/DemoBottomSheet.gif)

## DemoBottomModalSheet

模态的底部弹出 Widget。

![DemoBottomModalSheet](./img/DemoBottomModalSheet.gif)

## DemoRefreshIndicator

Android 风格的下拉刷新

![DemoRefreshIndicator](./img/DemoRefreshIndicator.gif)

## DemoBottomNavigationBar

底部导航

![DemoBottomNavigationBar](./img/DemoBottomNavigationBar.gif)

## DemoDrawer

抽屉效果。

![DemoDrawer](./img/DemoDrawer.gif)

## DemoClip

Widget 裁剪。可以利用 

ClipOval 裁剪出圆形、椭圆形

ClipRRect 裁剪圆角矩形

ClipRect 裁剪矩形

ClipPath 自定义裁剪路径

![DemoClip](./img/DemoClip.gif)

## DemoBackdropFilter

BackdropFilter 可以实现背景模糊

![DemoBackdropFilter](./img/DemoBackdropFilter.gif)

## DemoCustomPainter

CustomPainter 可以自定义painter绘制点、线、圆、扇形、弧形或定义路径实现复杂形状

![DemoCustomPainter](./img/DemoCustomPainter.gif)

## DemoNavigationRail

响应式导航

![DemoNavigationRail](./img/DemoNavigationRail.gif)

## DemoSliverAppBarBasic

SliverAppBar的基本使用

![DemoSliverAppBarBasic](./img/DemoSliverAppBarBasic.gif)

## DemoSliverAppBarAdvance

SliverAppBar 和 TabBarView 一起使用

![DemoSliverAppBarAdvance](./img/DemoSliverAppBarAdvance.gif)

## DemoCustomScrollView

自定义 CustomScrollView 支持嵌套各种布局，如 List、Grid 等

![DemoCustomScrollView](./img/DemoCustomScrollView.gif)

## DemoScrollController

滚动控制器，可以监听滚动过程中的位移。

![DemoScrollController](./img/DemoScrollController.gif)

## DemoScrollNotification

滚动监听，可以监听滚动过程中的位移。

![DemoScrollNotification](./img/DemoScrollNotification.gif)

## DemoRefreshLoadMore

简单自定义的下拉刷新和加载更多

![DemoRefreshLoadMore](./img/DemoRefreshLoadMore.gif)

## DemoCustomTimePicker

自定义时间选择控件

![DemoCustomTimePicker](./img/DemoCustomTimePicker.gif)

## DemoLifecycle

StatefulWidget 生命周期 

![DemoLifecycle](./img/DemoLifecycle.gif)

## DemoStateProvider

使用 Provider 实现的状态管理

![DemoStateProvider](./img/DemoStateProvider.gif)

## DemoInheritedWidget
