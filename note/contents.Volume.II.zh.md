# 目录
 
-  译者序
-  前言


-  第1章 Java SE 8的流库 1
    -  1.1 从迭代到流的操作 1
    -  1.2 流的创建 3
    -  1.3 filter、map和flatMap方法 6
    -  1.4 抽取子流和连接流 8
    -  1.5 其他的流转换 8
    -  1.6 简单约简 9
    -  1.7 Optional类型 11
        -  1.7.1 如何使用Optional值 11
        -  1.7.2 不适合使用Optional值的方式 12
        -  1.7.3 创建Optional值 13
        -  1.7.4 用flatMap来构建Optional值的函数 13
    -  1.8 收集结果 15
    -  1.9 收集到映射表中 19
    -  1.10 群组和分区 23
    -  1.11 下游收集器 24
    -  1.12 约简操作 28
    -  1.13 基本类型流 29
    -  1.14 并行流 34
    
-  第2章 输入与输出 39
    -  2.1 输入／输出流 39
        -  2.1.1 读写字节 39
        -  2.1.2 完整的流家族 42
        -  2.1.3 组合输入／输出流过滤器 45
    -  2.2 文本输入与输出 48
        -  2.2.1 如何写出文本输出 49
        -  2.2.2 如何读入文本输入 51
        -  2.2.3 以文本格式存储对象 52
        -  2.2.4 字符编码方式 55
    -  2.3 读写二进制数据 57
        -  2.3.1 DataInput和DataOutput接口 57
        -  2.3.2 随机访问文件 59
        -  2.3.3 ZIP文档 63
    -  2.4 对象输入／输出流与序列化 66
        -  2.4.1 保存和加载序列化对象 66
        -  2.4.2 理解对象序列化的文件格式 70
        -  2.4.3 修改默认的序列化机制 75
        -  2.4.4 序列化单例和类型安全的枚举 77
        -  2.4.5 版本管理 78
        -  2.4.6 为克隆使用序列化 80
    -  2.5 操作文件 83
        -  2.5.1 Path 83
        -  2.5.2 读写文件 85
        -  2.5.3 创建文件和目录 87
        -  2.5.4 复制、移动和删除文件 88
        -  2.5.5 获取文件信息 89
        -  2.5.6 访问目录中的项 91
        -  2.5.7 使用目录流 92
        -  2.5.8 ZIP文件系统 95
    -  2.6 内存映射文件 96
        -  2.6.1 内存映射文件的性能 96
        -  2.6.2 缓冲区数据结构 103
        -  2.6.3 文件加锁机制 105
    -  2.7 正则表达式 106
    
-  第3章 XML 117
    -  3.1 XML概述 117
        -  3.1.1 XML文档的结构 119
    -  3.2 解析XML文档 122
    -  3.3 验证XML文档 132
        -  3.3.1 文档类型定义 133
        -  3.3.2 XML Schema 139
        -  3.3.3 实用示例 142
    -  3.4 使用XPath来定位信息 154
    -  3.5 使用命名空间 159
    -  3.6 流机制解析器 162
        -  3.6.1 使用SAX解析器 162
        -  3.6.2 使用StAX解析器 166
    -  3.7 生成XML文档 170
        -  3.7.1 不带命名空间的文档 170
        -  3.7.2 带命名空间的文档 170
        -  3.7.3 写出文档 171
        -  3.7.4 示例：生成SVG文件 172
        -  3.7.5 使用StAX写出XML文档 174
    -  3.8 XSL转换 181
    
-  第4章 网络 191
    -  4.1 连接到服务器 191
        -  4.1.1 使用telnet 191
        -  4.1.2 用Java连接到服务器 193
        -  4.1.3 套接字超时 195
        -  4.1.4 因特网地址 196
    -  4.2 实现服务器 198
        -  4.2.1 服务器套接字 198
        -  4.2.2 为多个客户端服务 201
        -  4.2.3 半关闭 204
    -  4.3 可中断套接字 205
    -  4.4 获取Web数 211
        -  4.4.1 URL和URI 211
        -  4.4.2 使用URLConnection获取信息 213
        -  4.4.3 提交表单数据 220
    -  4.5 发送E—mail 228
    
-  第5章 数据库编程 232
    -  5.1 JDBC的设计 232
        -  5.1.1 JDBC驱动程序类型 233
        -  5.1.2 JDBC的典型用法 234
    -  5.2 结构化查询语言 234
    -  5.3 JDBC配置 239
        -  5.3.1 数据库URL 240
        -  5.3.2 驱动程序JAR文件 240
        -  5.3.3 启动数据库 240
        -  5.3.4 注册驱动器类 241
        -  5.3.5 连接到数据库 242
    -  5.4 使用JDBC语句 244
        -  5.4.1 执行SQL语句 244
        -  5.4.2 管理连接、语句和结果集 247
        -  5.4.3 分析SQL异常 248
        -  5.4.4 组装数据库 250
    -  5.5 执行查询操作 254
        -  5.5.1 预备语句 254
        -  5.5.2 读写LOB 259
        -  5.5.3 SQL转义 261
        -  5.5.4 多结果集 262
        -  5.5.5 获取自动生成的键 263
    -  5.6 可滚动和可更新的结果集 263
        -  5.6.1 可滚动的结果集 264
        -  5.6.2 可更新的结果集 266
    -  5.7 行集 269
        -  5.7.1 构建行集 270
        -  5.7.2 被缓存的行集 270
    -  5.8 元数据 273
    -  5.9 事务 282
        -  5.9.1 用JDBC对事务编程 282
        -  5.9.2 保存点 283
        -  5.9.3 批量更新 283
        -  5.10 高级SQL类型 285
        -  5.11 Web与企业应用中的连接管理 286
        
-  第6章 日期和时间API 288
    -  6.1 时间线 288
    -  6.2 本地时间 291
    -  6.3 日期调整器 294
    -  6.4 本地时间 295
    -  6.5 时区时间 296
    -  6.6 格式化和解析 299
    -  6.7 与遗留代码的互操作 302
    
-  第7章 国际化 304
    -  7.1 Locale对象 304
    -  7.2 数字格式 309
    -  7.3 货币 314
    -  7.4 日期和时间 315
    -  7.5 排序和范化 321
    -  7.6 消息格式化 327
        -  7.6.1 格式化数字和日期 327
        -  7.6.2 选择格式 329
    -  7.7 文本文件和字符集 331
        -  7.7.1 文本文件 331
        -  7.7.2 行结束符 331
        -  7.7.3 控制台 331
        -  7.7.4 日志文件 332
        -  7.7.5 UTF—8字节顺序标志 332
        -  7.7.6 源文件的字符编码 333
    -  7.8 资源包 333
        -  7.8.1 定位资源包 334
        -  7.8.2 属性文件 335
        -  7.8.3 包类 335
    -  7.9 一个完整的例子 337
    
-  第8章 脚本、编译与注解处理 352
    -  8.1 Java平台的脚本 352
        -  8.1.1 获取脚本引擎 352
        -  8.1.2 脚本赋值与绑定 353
        -  8.1.3 重定向输入和输出 355
        -  8.1.4 调用脚本的函数和方法 356
        -  8.1.5 编译脚本 357
        -  8.1.6 一个示例：用脚本处理GUI事件 358
    -  8.2 编译器API 363
        -  8.2.1 编译便捷之法 363
        -  8.2.2 使用编译工具 363
        -  8.2.3 一个示例：动态Java代码生成 368
    -  8.3 使用注解 373
        -  8.3.1 注解简介 373
        -  8.3.2 一个示例：注解事件处理器 374
    -  8.4 注解语法 379
        -  8.4.1 注解接口 379
        -  8.4.2 注解 380
        -  8.4.3 注解各类声明 382
        -  8.4.4 注解类型用法 383
        -  8.4.5 注解this 384
    -  8.5 标准注解 385
        -  8.5.1 用于编译的注解 386
        -  8.5.2 用于管理资源的注解 386
        -  8.5.3 元注解 387
    -  8.6 源码级注解处理 389
        -  8.6.1 注解处理 389
        -  8.6.2 语言模型API 390
        -  8.6.3 使用注解来生成源码 390
    -  8.7 字节码工程 393
        -  8.7.1 修改类文件 393
        -  8.7.2 在加载时修改字节码 398
        
-  第9章 安全 401
    -  9.1 类加载器 401
        -  9.1.1 类加载过程 402
        -  9.1.2 类加载器的层次结构 403
        -  9.1.3 将类加载器作为命名空间 404
        -  9.1.4 编写你自己的类加载器 405
        -  9.1.5 字节码校验 410
    -  9.2 安全管理器与访问权限 414
        -  9.2.1 权限检查 414
        -  9.2.2 Java平台安全性 415
        -  9.2.3 安全策略文件 418
        -  9.2.4 定制权限 424
        -  9.2.5 实现权限类 426
    -  9.3 用户认证 431
        -  9.3.1 JAAS框架 431
        -  9.3.2 JAAS登录模块 437
    -  9.4 数字签名 445
        -  9.4.1 消息摘要 445
        -  9.4.2 消息签名 448
        -  9.4.3 校验签名 449
        -  9.4.4 认证问题 452
        -  9.4.5 证书签名 454
        -  9.4.6 证书请求 454
        -  9.4.7 代码签名 455
    -  9.5 加密 460
        -  9.5.1 对称密码 461
        -  9.5.2 密钥生成 462
        -  9.5.3 密码流 466
        -  9.5.4 公共密钥密码 467
        
-  第10章 高级Swing 472
    -  10.1 列表 472
        -  10.1.1 JList构件 472
        -  10.1.2 列表模式 477
        -  10.1.3 插入和移除值 481
        -  10.1.4 值的绘制 482
    -  10.2 表格 486
        -  10.2.1 简单表格 486
        -  10.2.2 表格模型 489
        -  10.2.3 对行和列的操作 493
            -  10.2.3.1 各种列类 493
            -  10.2.3.2 访问表格列 493
            -  10.2.3.3 改变列的大小 494 
            -  10.2.3.4 改变行的大小 494
            -  10.2.3.5 选择行、列和单元格 495
            -  10.2.3.6 对行排序 495
            -  10.2.3.7 过滤行 497
            -  10.2.3.8 隐藏和显示列 498        
        -  10.2.4 单元格的绘制和编辑 506
            -  10.2.4.1 绘制单元格 506
            -  10.2.4.2 绘制表头 507
            -  10.2.4.3 单元格编辑 507
            -  10.2.4.4 定制编辑器 509        
    -  10.3 树 517
        -  10.3.1 简单的树 518
        -  10.3.2 编辑树和树的路径 524
        -  10.3.3 节点枚举 530
        -  10.3.4 绘制节点 532
        -  10.3.5 监听树事件 534
        -  10.3.6 定制树模型 541
    -  10.4 文本构件 548
        -  10.4.1 文本构件中的修改跟踪 549
        -  10.4.2 格式化的输入框 552
            -  10.4.2.1 整数输入 553
            -  10.4.2.2 失去焦点时的行为 554
            -  10.4.2.3 过滤器 554
            -  10.4.2.4 校验器 556
            -  10.4.2.5 其他的标准格式器 556
            -  10.4.2.6 定制格式器 558
        -  10.4.3 JSpinner构件 567
        -  10.4.4 用JEditorPane显示HTML 574
    -  10.5 进度指示器 579
        -  10.5.1 进度条 580
        -  10.5.2 进度监视器 582
        -  10.5.3 监视输入流的进度 585
    -  10.6 构件组织器和装饰器 590
        -  10.6.1 分割面板 590
        -  10.6.2 选项卡面板 592
        -  10.6.3 桌面面板和内部框体 597
            -  10.6.3.1 显示内部框体 598
            -  10.6.3.2 级联与平铺 600
            -  10.6.3.3 否决属性设置 603
            -  10.6.3.4 内部框体中的对话框 605
            -  10.6.3.5 边框拖拽 605
        -  10.6.4 层 613
        
-  第11章 高级AWT 618
    -  11.1 绘图操作流程 618
    -  11.2 形状 620
        -  11.2.1 形状类层次结构 621
        -  11.2.2 使用形状类 623
    -  11.3 区域 634
    -  11.4 笔划 635
    -  11.5 着色 642
    -  11.6 坐标变换 644
    -  11.7 剪切 648
    -  11.8 透明与组合 650
    -  11.9 绘图提示 657
    -  11.10 图像的读取器和写入器 663
        -  11.10.1 获得适合图像文件类型的读取器和写入器 663
        -  11.10.2 读取和写入带有多个图像的文件 664
    -  11.11 图像处理 671
        -  11.11.1 构建光栅图像 672
        -  11.11.2 图像过滤 678
    -  11.12 打印 685
        -  11.12.1 图形打印 685
        -  11.12.2 打印多页文件 693
        -  11.12.3 打印预览 694
        -  11.12.4 打印服务程序 702
        -  11.12.5 流打印服务程序 706
        -  11.12.6 打印属性 707
    -  11.13 剪贴板 712
        -  11.13.1 用于数据传递的类和接口 713
        -  11.13.2 传递文本 714
        -  11.13.3 Transferable接口和数据风格 717
        -  11.13.4 构建一个可传递的图像 718
        -  11.13.5 通过系统剪贴板传递Java对象 722
        -  11.13.6 使用本地剪贴板来传递对象引用 725
    -  11.14 拖放操作 725
        -  11.14.1 Swing对数据传递的支持 726
        -  11.14.2 拖曳源 730
        -  11.14.3 放置目标 732
    -  11.15 平台集成 739
        -  11.15.1 闪屏 739
        -  11.15.2 启动桌面应用程序 743
        -  11.15.3 系统托盘 748

-  第12章 本地方法 752
    -  12.1 从Java程序中调用C函数 752
    -  12.2 数值参数与返回值 757
    -  12.3 字符串参数 759
    -  12.4 访问域 764
        -  12.4.1 访问实例域 765
        -  12.4.2 访问静态域 768
    -  12.5 编码签名 769
    -  12.6 调用Java方法 770
        -  12.6.1 实例方法 771
        -  12.6.2 静态方法 774
        -  12.6.3 构造器 775
        -  12.6.4 另一种方法调用 775
    -  12.7 访问数组元素 777
    -  12.8 错误处理 780
    -  12.9 使用调用API 785
    -  12.10 完整的示例：访问Windows注册表 789
        -  12.10.1 Windows注册表概述 789
        -  12.10.2 访问注册表的Java平台接口 791
        -  12.10.3 以本地方法方式实现注册表访问函数 791

