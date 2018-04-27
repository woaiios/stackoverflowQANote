# stackoverflowQANote

* [iPhone smooth sketch drawing algorithm](https://stackoverflow.com/q/5076622/9628756)


## tip

1. `Shift + Cmd + I `进行 Profiling 编译，可获得非 Debug 版本的 framework 。

   
    选择 Generic iOS Device 编译。打开 Products 目录，选中 xx.framework, Show in Finder, 确定 /Build/Products/Release-xx 的路径。
   
2. Xcode 搜索汉字
 正则表达式 `"[\u4e00-\u9fa5]+`
