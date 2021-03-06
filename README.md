
![](./images/logo.png)

## 一. iOS基础类面试题

### 1.1 内存管理相关

****内存管理****

* [iOS 内存分布是怎样的？有哪些区域，每个区域的作用](https://github.com/tbfungeek/iOS-Daily-Interview/issues/1)
* [谈谈iOS的内存管理方式的理解](https://github.com/tbfungeek/iOS-Daily-Interview/issues/2)
* [MRC、ARC和 Autorelease的区别](https://github.com/tbfungeek/iOS-Daily-Interview/issues/3)
* [ARC在编译时和运行时都做了哪些工作](https://github.com/tbfungeek/iOS-Daily-Interview/issues/7)
* [ARC 使用的过程中需要注意点以及遵循的原则](https://github.com/tbfungeek/iOS-Daily-Interview/issues/4)
* [ARC情况下有哪些限制](https://github.com/tbfungeek/iOS-Daily-Interview/issues/8)
* [介绍下NSZone](https://github.com/tbfungeek/iOS-Daily-Interview/issues/5)
* [说说你对assign，strong，weak，unsafe_unretained，copy的理解](https://github.com/tbfungeek/iOS-Daily-Interview/issues/6)
* [__weak 修饰的变量，是否已经被注册在了 @autoreleasePool 中？为什么？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/9)
* [ARC 的 retainCount 怎么存储的？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/10)
* [__weak 属性修饰的变量，如何实现在变量没有强引用后自动置为 nil？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/11)
* [说一下什么是 悬垂指针？什么是 野指针?](https://github.com/tbfungeek/iOS-Daily-Interview/issues/12)
* [BAD_ACCESS 在什么情况下出现?](https://github.com/tbfungeek/iOS-Daily-Interview/issues/13)
* [retain、release 的实现机制是怎样的？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/14)
* [能不能简述一下 dealloc 的实现机制？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/15)
* [在 MRC 下如何重写属性的 Setter 和 Getter?](https://github.com/tbfungeek/iOS-Daily-Interview/issues/16)
* [介绍下@property、@synthesize和@dynamic的作用](https://github.com/tbfungeek/iOS-Daily-Interview/issues/17)

****AutoReleasePool相关****

* [什么是AutoReleasePool，它都有哪几种类型](https://github.com/tbfungeek/iOS-Daily-Interview/issues/18)
* [RunLoop AutoReleasePool的创建及释放时机是怎样的](https://github.com/tbfungeek/iOS-Daily-Interview/issues/19)
* [简要介绍下 @autoreleasePool 的数据结构？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/20)
* [函数返回一个对象时，会对对象 autorelease 么？为什么？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/21)
* [自动释放池的作用是什么](https://github.com/tbfungeek/iOS-Daily-Interview/issues/22)
* [AutoreleasePool drain 和 release区别](https://github.com/tbfungeek/iOS-Daily-Interview/issues/23)

****循环引用，内存泄漏相关****

* [日常开发中有哪些可能会出现的循环引用？又该怎样解决这些问题](https://github.com/tbfungeek/iOS-Daily-Interview/issues/24)
* [内存泄漏有几种类型？有哪些排查方式](https://github.com/tbfungeek/iOS-Daily-Interview/issues/25)

### 1.2 分类扩展与协议相关

* [分类的作用有哪些?](https://github.com/tbfungeek/iOS-Daily-Interview/issues/26)
* [分类与扩展的区别?](https://github.com/tbfungeek/iOS-Daily-Interview/issues/27)
* [通过分类可以为某个类添加哪些东西?](https://github.com/tbfungeek/iOS-Daily-Interview/issues/28)
* [分类的实现原理？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/29)
* [如何给分类添加属性？关联对象以什么形式进行存储？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/30)
* [分类可不可以添加实例对象？为什么？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/31)
* [分类在编译过后，是在什么时机与原有的类合并到一起的?](https://github.com/tbfungeek/iOS-Daily-Interview/issues/32)
* [分类与宿主类有同名方法会有什么结果?](https://github.com/tbfungeek/iOS-Daily-Interview/issues/33)
* [分类与其他分类有同名方法会有什么结果?](https://github.com/tbfungeek/iOS-Daily-Interview/issues/34)
* [协议可以添加属性吗？如果可以怎么添加。](https://github.com/tbfungeek/iOS-Daily-Interview/issues/35)

### 1.3 Block 相关

* [说一下什么是Block?](https://github.com/tbfungeek/iOS-Daily-Interview/issues/36)
* [Block 和 函数指针 的区别? ](https://github.com/tbfungeek/iOS-Daily-Interview/issues/37)
* [说下Block的对不同类型变量的捕获情况 ](https://github.com/tbfungeek/iOS-Daily-Interview/issues/38)
* [Block 有几种类型？分别是什么？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/39)
* [说说你对__block的理解，以及forwarding的作用](https://github.com/tbfungeek/iOS-Daily-Interview/issues/40)
* [对不同类型的block进行copy操作结果分别是怎样的？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/41)
* [哪些情况下block会被copy到堆上？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/42)
* [__block 的解释以及在 ARC 和 MRC 下有什么不同？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/43)
* [dispatch_block_t这个有没有用过？解释一下？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/44)

### 1.4 Runtime相关

* [实例对象的数据结构？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/45)
* [类对象及元类对象的数据结构?](https://github.com/tbfungeek/iOS-Daily-Interview/issues/46)
* [Obj-C 对象、类的本质是通过什么数据结构实现的？ ](https://github.com/tbfungeek/iOS-Daily-Interview/issues/47)
* [Obj-C 中的类信息存放在哪里？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/48)
* [一个 NSObject 对象占用多少内存空间？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/49)
* [说一下对 class_rw_t 结构体的理解？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/50)
* [说一下对 class_ro_t 的理解？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/51)
* [说一下对 isa 指针的理解，对象的 isa 指针指向哪里？ isa 指针有哪两种类型？（注意区分不同对象）](https://github.com/tbfungeek/iOS-Daily-Interview/issues/52)
* [说一下 Runtime 消息解析。](https://github.com/tbfungeek/iOS-Daily-Interview/issues/53)
* [说一下 Runtime 消息转发。](https://github.com/tbfungeek/iOS-Daily-Interview/issues/54)
* [说一下 Method Swizzling? 说一下在实际开发中你在什么场景下使用过? ](https://github.com/tbfungeek/iOS-Daily-Interview/issues/55)
* [如何运用 Runtime 字典转模型？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/56)
* [如何运用 Runtime 进行模型的归解档？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/57)
* [在 Obj-C 中为什么叫发消息而不叫函数调用？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/58)
* [说一下 Runtime 的方法缓存？存储的形式、数据结构以及查找的过程？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/59)
* [是否了解 Type Encoding? ](https://github.com/tbfungeek/iOS-Daily-Interview/issues/60)
* [Objective-C 如何实现多重继承？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/61)
* [说说+load +initializer区别](https://github.com/tbfungeek/iOS-Daily-Interview/issues/62)
* [说说Mach O的组成结构以及每个部分的作用](https://github.com/tbfungeek/iOS-Daily-Interview/issues/63)
* [说说点击App后到main方法经过的步骤](https://github.com/tbfungeek/iOS-Daily-Interview/issues/64)
* [class方法和objc_getClass方法有什么区别?](https://github.com/tbfungeek/iOS-Daily-Interview/issues/65)


### 1.5 KVC KVO 相关

* [说下KVC与普通的实例变量存取方法的区别](https://github.com/tbfungeek/iOS-Daily-Interview/issues/66)
* [说下KVC setValue:forKey:的搜索策略](https://github.com/tbfungeek/iOS-Daily-Interview/issues/67)
* [说下KVC valueForKey:的搜索策略](https://github.com/tbfungeek/iOS-Daily-Interview/issues/68)
* [说下KVC 常用的场景](https://github.com/tbfungeek/iOS-Daily-Interview/issues/69)
* [介绍下KVO的原理](https://github.com/tbfungeek/iOS-Daily-Interview/issues/70)
* [介绍下KVO的触发时机](https://github.com/tbfungeek/iOS-Daily-Interview/issues/71)
* [说说什么时候需要手动触发KVO](https://github.com/tbfungeek/iOS-Daily-Interview/issues/72)

### 1.6 多线程相关

* [介绍下iOS中的多线程的几种实现方案，及各自的特点](https://github.com/tbfungeek/iOS-Daily-Interview/issues/73)
* [创建太多线程会有什么影响](https://github.com/tbfungeek/iOS-Daily-Interview/issues/74)
* [说一下线程的生命周期](https://github.com/tbfungeek/iOS-Daily-Interview/issues/75)
[](https://github.com/tbfungeek/iOS-Daily-Interview/issues/77)
* [介绍下GCD的特点](https://github.com/tbfungeek/iOS-Daily-Interview/issues/76)
* [说下任务和队列组成的四种组合的情况](https://github.com/tbfungeek/iOS-Daily-Interview/issues/78)
* [介绍下GCD 任务组的作用](https://github.com/tbfungeek/iOS-Daily-Interview/issues/79)
* [介绍下dispatch_group_enter/dispatch_group_leave和dispatch_group_async各自的应用场景以及使用的时候需要注意哪些问题](https://github.com/tbfungeek/iOS-Daily-Interview/issues/80)
* [介绍下dispatch_barrier_async的应用场景](https://github.com/tbfungeek/iOS-Daily-Interview/issues/81)
* [介绍下你所知道的NSOperation 和 NSOperationQueue的相关内容](https://github.com/tbfungeek/iOS-Daily-Interview/issues/82)
* [NSOperation如何实现串行](https://github.com/tbfungeek/iOS-Daily-Interview/issues/83)
* [如何实现线性编程？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/84)
* [说一下 GCD 并发队列实现机制？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/85)
* [说一下你了解的iOS开发中的各种锁](https://github.com/tbfungeek/iOS-Daily-Interview/issues/86)
* [NSLock使用的时候需要注意哪些](https://github.com/tbfungeek/iOS-Daily-Interview/issues/87)
* [为什么需要递归锁，它解决的问题是什么](https://github.com/tbfungeek/iOS-Daily-Interview/issues/88)
* [Synchronized 的实现机制](https://github.com/tbfungeek/iOS-Daily-Interview/issues/89)
* [说说自旋锁与互斥锁的区别，以及自旋锁适用的场景](https://github.com/tbfungeek/iOS-Daily-Interview/issues/90)
* [如何确保线程安全？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/91)
* [atomic 在保证线程安全使用方面要注意哪些问题](https://github.com/tbfungeek/iOS-Daily-Interview/issues/92)
* [NSMutableArray、和 NSMutableDictionary是线程安全的吗？NSCache呢?](https://github.com/tbfungeek/iOS-Daily-Interview/issues/93)
* [多线程的 并行 和 并发 有什么区别？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/94)
* [多线程有哪些优缺点？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/95)
* [如何自定义 NSOperation ? ](https://github.com/tbfungeek/iOS-Daily-Interview/issues/96)
* [GCD 与 NSOperationQueue 有哪些异同？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/97)
* [解释一下多线程中的死锁？，死锁的条件，以及死锁的解决方案](https://github.com/tbfungeek/iOS-Daily-Interview/issues/98)
* [解释一下多线程中的优先级反转？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/99)
* [子线程是否会出现死锁？说一下场景？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/100)
* [多线程技术在使用过程中有哪些注意事项？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/101)

### 1.7 RunLoop相关

* [Runloop 和线程的关系？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/102)
* [讲一下 Runloop 的 Mode?](https://github.com/tbfungeek/iOS-Daily-Interview/issues/103)
* [讲一下 Observer ？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/104)
* [讲一下 Source ？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/105)
* [讲一下 Runloop 的内部实现逻辑？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/106)
* [你所知的哪些三方框架使用了 Runloop?](https://github.com/tbfungeek/iOS-Daily-Interview/issues/107)
* [AutoreleasePool 在何时被释放？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/108)
* [解释一下 事件响应 的过程？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/109)
* [解释一下 手势识别 的过程？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/110)
* [解释一下 GCD 在 Runloop 中的使用？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/111)
* [解释一下 NSTimer与Runloop的关系。](https://github.com/tbfungeek/iOS-Daily-Interview/issues/112)
* [AFNetworking 中如何运用 Runloop?](https://github.com/tbfungeek/iOS-Daily-Interview/issues/113)
* [PerformSelector 的实现原理？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/114)
* [利用 Runloop 解释一下页面的渲染的过程？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/115)
* [如何使用 Runloop 实现一个常驻线程？这种线程一般有什么作用](https://github.com/tbfungeek/iOS-Daily-Interview/issues/116)
* [为什么 NSTimer 有时候不好使？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/117)
* [PerformSelector:afterDelay:这个方法在子线程中是否起作用？为什么？怎么解决？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/118)
* [介绍下定时执行有几种方式](https://github.com/tbfungeek/iOS-Daily-Interview/issues/119)
* [如何检测 App 运行过程中是否卡顿？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/120)
* [简单介绍下你所知道的Runloop的应用](https://github.com/tbfungeek/iOS-Daily-Interview/issues/121)

### 1.8 UI 相关

#### 1.8.1 生命周期相关

* [介绍下应用有哪些状态](https://github.com/tbfungeek/iOS-Daily-Interview/issues/122)
* [介绍下，冷启动，热启动，锁屏，解锁，按Home进入后台，其他应用中断了当前应用，重新回到当前应用这些情况都会调用哪些方法](https://github.com/tbfungeek/iOS-Daily-Interview/issues/123)
* [应用如何在后台保活](https://github.com/tbfungeek/iOS-Daily-Interview/issues/124)
* [介绍下应用的生命周期](https://github.com/tbfungeek/iOS-Daily-Interview/issues/125)
* [介绍下UIView的生命周期](https://github.com/tbfungeek/iOS-Daily-Interview/issues/126)
* [介绍下UIViewController的生命周期](https://github.com/tbfungeek/iOS-Daily-Interview/issues/127)
* [loadView方法了解吗？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/128)
* [说一下控制器 View 的生命周期，一旦收到内存警告会如何处理？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/129)
* [说下什么情况下会触发约束的自动更新，怎么手动更新约束](https://github.com/tbfungeek/iOS-Daily-Interview/issues/130)
* [说下什么情况下会触发布局的自动更新，怎么手动更新布局](https://github.com/tbfungeek/iOS-Daily-Interview/issues/131)
* [说下什么情况下会自动触发绘制，怎么手动触发绘制](https://github.com/tbfungeek/iOS-Daily-Interview/issues/132)

#### 1.8.2 渲染相关

* [简要介绍下iOS 渲染框架组成](https://github.com/tbfungeek/iOS-Daily-Interview/issues/133)
* [为什么要存在UIView和CALayer，说说它们的区别及联系](https://github.com/tbfungeek/iOS-Daily-Interview/issues/134)
* [介绍下绘制流程](https://github.com/tbfungeek/iOS-Daily-Interview/issues/135)
* [说下渲染的整个过程，以及CPU,GPU各做了哪些工作](https://github.com/tbfungeek/iOS-Daily-Interview/issues/136)
* [说下什么是离屏渲染，触发离屏渲染的因素，为什么离屏渲染会比较耗时，要如何解决这些问题](https://github.com/tbfungeek/iOS-Daily-Interview/issues/137)
* [说说绘图上下文的作用,iOS有哪些绘图上下文类型](https://github.com/tbfungeek/iOS-Daily-Interview/issues/138)
* [CGContextSaveGState/CGContextRestoreGState 与 UIGraphicsPushContext/UIGraphicsPopContext区别](https://github.com/tbfungeek/iOS-Daily-Interview/issues/139)
* [CGPath 和 UIBezierPath() 区别](https://github.com/tbfungeek/iOS-Daily-Interview/issues/140)

#### 1.8.3 布局相关

* [简要介绍下frame, bounds, position，center，anchorPoint这些属性](https://github.com/tbfungeek/iOS-Daily-Interview/issues/141)
* [有哪几种布局方式](https://github.com/tbfungeek/iOS-Daily-Interview/issues/142)
* [说说AutoLayout 工作原理](https://github.com/tbfungeek/iOS-Daily-Interview/issues/143)
* [说说bounds 和 Frame 的区别?](https://github.com/tbfungeek/iOS-Daily-Interview/issues/144)
* [说说你知道的三方布局开源库，简要对比下，它们的优缺点](https://github.com/tbfungeek/iOS-Daily-Interview/issues/145)
* [UITableViewCell 如何根据 UILabel 内容长度自动调整高度](https://github.com/tbfungeek/iOS-Daily-Interview/issues/146)

#### 1.8.4 动画相关

* [简要介绍下动画所涉及到的哪些类，它们的继承关系是怎样的](https://github.com/tbfungeek/iOS-Daily-Interview/issues/147)
* [说说动画的事务管理](https://github.com/tbfungeek/iOS-Daily-Interview/issues/148)
* [什么情况下会有隐式动画，为什么会有隐式动画](https://github.com/tbfungeek/iOS-Daily-Interview/issues/149)
* [说说presentingViewController和presentedViewController的区别](https://github.com/tbfungeek/iOS-Daily-Interview/issues/150)
* [如何暂停一个 UIView 中正在播放的动画？暂停后如何恢复？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/151)

#### 1.8.5 事件相关

* [说说iOS有哪些事件源类型](https://github.com/tbfungeek/iOS-Daily-Interview/issues/152)
* [哪些对象能够响应事件，这些对象的共同点是什么？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/153)
* [说说touchesBegan/touchesMoved/touchesEnded/touchesCancelled的作用](https://github.com/tbfungeek/iOS-Daily-Interview/issues/154)
* [说说iOS上的事件对象有哪些相关的类，它们之间的关系是怎样的？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/155)
* [介绍下事件的传递流程](https://github.com/tbfungeek/iOS-Daily-Interview/issues/156)
* [介绍下构建响应链的流程，及事件响应流程](https://github.com/tbfungeek/iOS-Daily-Interview/issues/157)
* [说下手势有哪些状态？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/158)
* [说下事件和手势共存的情况下的事件处理流程](https://github.com/tbfungeek/iOS-Daily-Interview/issues/159)
* [说下常见的事件冲突和解决方案](https://github.com/tbfungeek/iOS-Daily-Interview/issues/160)

### 1.9 其他

* [UIButton 的父类是什么？UILabel 的父类又是什么？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/161)
* [实现一个控件，可以浮在任意界面的上层并支持拖动？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/162)
* [如何以通用的方法找到当前显示的ViewController?](https://github.com/tbfungeek/iOS-Daily-Interview/issues/163)
* [setNeedsDisplay 和 layoutIfNeeded 两者是什么关系？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/164)
* [nil、NIL、NSNULL 有什么区别？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/165)
* [如何实现一个线程安全的 NSMutableArray?](https://github.com/tbfungeek/iOS-Daily-Interview/issues/166)
* [atomic 修饰的属性是绝对安全的吗？为什么？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/167)
* [实现 isEqual 和 hash 方法时要注意什么](https://github.com/tbfungeek/iOS-Daily-Interview/issues/168)
* [id 和 instanceType 有什么区别？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/169)
* [说一下对 Super 关键字的理解](https://github.com/tbfungeek/iOS-Daily-Interview/issues/170)
* [@synthesize 和 @dynamic 分别有什么作用？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/172)
* [头文件导入的方式？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/175)
* [如何将 Obj-C 代码改变为 C++/C 的代码？](https://github.com/tbfungeek/iOS-Daily-Interview/issues/176)
* [如何定义一台 iOS 设备的唯一性?](https://github.com/tbfungeek/iOS-Daily-Interview/issues/178)

## 二. iOS高级面试题

### 2.1 性能优化相关

### 2.2 动态化相关

### 2.3 组件化相关

### 2.4 热修复相关


## 三. iOS三方开源库相关面试题


## 四. 通用技术相关

### 4.1 网络相关

### 4.2 设计模式相关

### 4.3 架构相关

### 4.4 数据结构/算法相关


## 五. 面试前必读材料

### 4.1 源码类

### 4.2 博客类

### 4.3 开源库

### 4.4 书籍
