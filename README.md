# flutter_app_zuiquan_kuangjia_xin

即墨商管框架模板，已经封装好，已经封装好 增加了中文 国际化 ， input 框 复制粘贴 英文改成了中文 ， 点击两次 退出 APP ，开屏页启动图 ，登录页面 ，路由 ，状态管理 ，全局常量 Sting，color，wordstyle文字样式，状态栏样式，强制竖屏，全局弹框 ，全局api ，增加了仿微信通讯录，增加了夜间模式，框架适用于flutter SDK 1.12.13版本


version: 1.0.0+1

environment:
  sdk: ">=2.1.0 <3.0.0"

dependencies:
  flutter:
    sdk: flutter
  flutter_localizations:
    sdk: flutter
  cupertino_icons: 0.1.3  # 自带的图标插件
  json_annotation: 3.0.1    #通过`json_serializable`包支持JSON代码生成的类和辅助函数。
  dio: 3.0.9                  #http请求
  flutter_spinkit: 4.1.2      #随时间变化而变化的加载指示器集合  加载器
  event_bus: 1.1.1           #使用Dart Streams进行应用程序去耦的简单事件总线  事件传递
  flutter_webview_plugin: 0.3.10+1   #允许Flutter与本机WebView通信的插件
  flutter_screenutil: 1.0.2    #一个用于调整屏幕和字体大小的Flutter插件，保证在不同型号上看起来都不错
  fluttertoast: 3.1.3           #提示信息
  shared_preferences: 0.5.6+3   #本地存储数据
  fluro: 1.6.1       #Fluro是Flutter路由库，它添加了灵活的路由选项
  provider: 4.0.4    #依赖项注入和状态管理之间的混合，使用用于小部件的小部件构建。
  permission_handler: 4.4.0      #Flutter的权限插件。此插件提供了一个跨平台（iOS，Android）API来请求和检查权限。
  url_launcher: 5.4.2       #用于在移动平台中启动URL。支持iOS和Android。
  cached_network_image: 2.0.0   #图片用于缓存管理
  azlistview: 0.1.2   # Flutter 城市列表，联系人列表，索引&悬停 https://github.com/flutterchina/azlistview
  lpinyin: 1.0.9      # Dart 汉字转拼音 https://github.com/flutterchina/lpinyin
  flustars: 0.2.6+1                  #简单易用工具类
  photo: 0.4.8    #用于选择图像，支持多选，而且这个是用Flutter做的UI，可以很方便的自定义修改（强烈推荐）。
  
  
#  bot_toast: 2.3.0       #一个非常易于使用的Flutter Toast库，易于使用且功能丰富。
#  reorderables: 0.3.2    #包括可重新排序的表，行，列，换行和条状列表，使它们的子级可拖动并在小部件内重新排序。
#  flutter_easyrefresh: 2.1.0   #提供给颤动滚动组件的小部件可下拉刷新并上拉负载。
#  flutter_swiper: 1.1.6     #轮播
#  flutter_html: 0.11.1        #用于将静态html标签呈现为Flutter小部件
#  flutter_native_timezone: 1.0.4   #一个flutter插件，用于获取操作系统的本地时区。
#  network_to_file_image: 2.2.8  #缓存图片到本地
#  image_picker: 0.6.3+4    #图片选择相机或者拍照
#  multi_image_picker: 4.6.2    #多图片选择上传
#  image_gallery_saver: 1.2.2   #用于将图像保存到图库，iOS需要将以下密钥添加到Info.plist文件中。
#  image_picker_saver: 0.3.0   #并添加了保存图像功能以将图像保存到图库。支援Android   IOS支持8.0+
#  path_provider: 1.6.5     #路径获取
#  persist_theme: 1.5.1  #用于持久和动态更改主题。
#  photo_view: 0.9.2              #缩放图片预览图片轮播
#  loader_search_bar: 1.0.3+3      #导航栏搜索信息插件
#  flappy_search_bar: 1.7.2      #导航栏搜索信息插件
#  fluwx: 2.0.4                   #微信登录，分享，支付
#  tobias: 1.4.0              #支付宝支付
#  alipay_me: 1.0.0           #支持付款和授权登录
#  extended_image: 0.7.1        #支持占位符（加载）/失败状态，缓存网络，缩放平移图像，照片视图
#  cool_ui: 0.4.1                #用flutter实现一些我认为好看的UI控件
#  flutter_image_compress: 0.6.5+1     #压缩图片
#  flutter_video_compress: 0.3.7+8   #压缩视频
#  flutter_progress_hud: 1.0.2        #全屏加载框
#  open_file: 3.0.1                 #打开文件插件
#  image_crop: 0.3.2                #Flutter的图像裁剪插件
#  flutter_downloader: 1.4.1       #下载文件
#  progress_dialog: 1.2.1        #加载框
#  blue_thermal_printer: 1.0.9    #Flutter插件，用于通过蓝牙连接到热敏打印机，暂时只支持安卓
#  flutter_blue: 0.5.0        #FlutterBlue是Flutter的蓝牙插件
#  bluetooth_print: 2.0.0     #可帮助开发人员为iOS和Android构建蓝牙热敏打印机应用程序
#  esc_pos_bluetooth: 0.2.4   #该库允许使用蓝牙打印机打印收据
#  esc_pos_printer: 3.1.4     #该库允许使用ESC / POS热WiFi /以太网打印机打印收据。
#  flutter_bluetooth_print_plugin: 1.0.0   #Flutter Connect蓝牙打印机插件。
#  barcode_scan: 2.0.1   #一个Flutter插件，用于扫描2D条码和QR码。
#  flutter_barcode_scanner: 0.1.7  #Flutter应用程序插件，在Android和iOS上均添加了条形码扫描支持。
#  intl: 0.16.1    #该软件包提供国际化和本地化功能，包括消息翻译，复数形式和性别，日期/数字格式和解析以及双向文本。
#  zefyr: 0.10.0   #富文本编辑器
#  flutter_l10n: 0.1.3  #国际化适配
#  fluintl: 0.1.3    #是一个为应用提供国际化的库，可快速集成实现应用多语言。
#  flutter_apple_pay: 0.1.3    #苹果内部支付
#  flutter_aes_ecb_pkcs5: 0.1.1   #提供AES密钥的加密
#  crypto: 2.1.3     #在纯Dart中实现的一组加密哈希函数
#  flutter_advanced_networkimage: 0.7.0   #高级图像缓存加载和缩放控制
#  transparent_image: 1.0.0       #简单的透明图像，表示为Uint8List。在加载图片时可以用来做为占位符。
#  image_jpeg: 1.1.1    #用于图像上传之前转jpeg缩放压缩，调用Android或iOS原生功能进行处理，性能较高，支持的源图像格式也更多。
#  carousel_slider: 1.4.1  #一个支持手势划动和自动播放的图像展示控件。
#  parallax_image: 0.3.1+1   #视差图像可以与任何可滚动（例如ListVIEW）一起使用。说白了就是让放在滚动区域内的图像滚动时看起来更平滑。
#  zoomable_image: 1.3.1  #提供图像查看和手势缩放操作功能。

#  camera: 0.5.7+4   #用于在Android和iOS上获取有关和控制相机的信息。支持预览相机馈送和捕捉图像。
#  flutter_picker: 1.1.3  #选择器。可以根据json或自定义数据生成选择器。
#  extended_nested_scroll_view: 0.4.0   #一个扩展NestedScrollView，能够更好的处理列表、TabView、Sliver混合的情况
#  bottom_navigation_badge: 1.0.3    #允许开发人员将通知徽章添加到底部导航栏项数量    红点数量
#  flutter_app_badger: 1.1.2      #用于在启动器上更新应用程序徽章的插件（适用于Android和iOS）  红点数量
#  badges: 1.1.1    #徽章可用于任何小部件的附加标记，例如，显示购物车中的许多物品。   红点数量
#  getflutter: 1.0.10    #GetFlutter是带有预构建的1000+ UI组件的开源库。它使开发更快，更愉快。您可以根据需要自定义组件。**************************重点
#  ff_contact_avatar: 0.1.1   #用于显示带有姓名和短信的联系人头像。
#  onesignal_flutter: 2.3.4   #针对移动应用程序的免费推送通知服务。此SDK可轻松将Flutter iOS和/或Android应用程序与OneSignal集成。
#  notification_permissions: 0.4.4   #用于在iOS和Android上检查并询问通知权限的软件包。
#  flutter_staggered_grid_view: 0.3.0   # 响应式瀑布流插件

dev_dependencies:
  flutter_test:
    sdk: flutter
#  build_runner: 1.8.0
#  json_serializable: 3.2.5
