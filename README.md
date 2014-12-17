# 无线端使用仿真器调试（提供webview搭建源码）

## 优缺点
## IOS
  - 解压缩ios-webview.zip
  - 使用Xcode打开工程
  - 修改 ViewController.m文件 
    - NSURLRequest *request =[NSURLRequest requestWithURL:[NSURL URLWithString:@"http://xx.html"]];//xx将为要调试的html名称
  - 运行即可在仿真器显示应用
  - 打开safari，在safari菜单》开发》iphone simulator 就可以利用safari在里面调试webview中h5的代码
     
![](images/ios-debug.png)
     

## Android

- 解压缩ios-webview.zip
- 工程导入到eclipse ADT中
- 启动AVD运行程序，程序会让你首先输入要测试的网址 输入后点击 click me 进入调试的页面
- 使用Chrome的远程即可调试 chrome://inspect/#devices


