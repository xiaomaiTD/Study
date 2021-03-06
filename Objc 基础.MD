
#### ObjC 基础
##### 为什么说OC是动态语言?
* [阿里云 - 为什么说Objective-C 是一门动态的语言 ](https://www.aliyun.com/jiaocheng/354015.html)
> 整体上说明动态性

* [为什么说 Objective-C 是一种动态语言?](https://blog.csdn.net/huangfei711/article/details/78262860)
> 从三个方面说明

* [Objective-C是动态语言吗？为什么？](https://www.zhihu.com/question/19970471)
> 从C++底层对动态性做些说明

##### 动态类型
* [逆向分析isKindOfClass 内部实](https://blog.csdn.net/ChSaDiN/article/details/51672087)
> 注意，类对象调用先取 object_getClass （取类的metaClass），实例调用取 isa 指针。
          
* [ObjC语法之动态类型 - isKindOfClass, isMemberOfClass](https://blog.csdn.net/totogo2010/article/details/7714960)
> 注意，[测试数据项目](https://github.com/skyming/Study/tree/master/01-Demo/BaseOC)

    
* [Design Patterns in iOS — Class Clusters](http://www.cocoachina.com/industry/20140530/8622.html)
> 注意，对字符串的分析
    
* [NSOederdSet](http://nshipster.cn/nsorderedset/)
> 思考多继承及类簇关系

##### 动态加载
* [iOS 组件化开发：加载资源](https://juejin.im/post/5ac6eb496fb9a028bb193b4a?utm_source=gold_browser_extension) 
> 注意动态加载图片、xib 区别、NSBundle 类相关方法

* [iOS 运行时：动态方法解决方案](http://michael1984w.blog.sohu.com/322918224.html)
> 注意动态加载理解

* [iOS编程基础-OC（七）-运行时系统（续）](https://blog.csdn.net/baby_hua/article/details/78723482)
> 关注延迟加载、bundle 加载机制

* [第九章 专家级技巧：使用运行时系统API](https://blog.csdn.net/baby_hua/article/details/78833425)
> 注意，使用可选包扩展正在运行的程序实践 

* [第九章 专家级技巧：使用运行时系统API续](https://blog.csdn.net/baby_hua/article/details/78862262)
> 注意，动态创建类、方法、属性，动态代理、AOP


#### 加载过程
* [iOS 中性能优化之 load 与 initialize](https://www.ctolib.com/topics-114981.html)
* [你真的了解 load 方法吗](https://zhuanlan.zhihu.com/p/20816991)
* [load方法全程跟踪](http://www.desgard.com/Load/)
* [懒惰的 initialize 方法](https://segmentfault.com/a/1190000005038568)
* [为什么要用 -all_load & -ObjC](https://yq.aliyun.com/articles/47656)
* [dyld 与 load](https://blog.cnbluebox.com/blog/2017/06/20/dyldyu-objc)

#### 内存相关
* [iOS内存管理和malloc源码解读](https://www.cnblogs.com/itsApe/p/5170108.html) 
* [说说iOS与内存管理（上）](http://www.cocoachina.com/ios/20150625/12234.html)
* [说说iOS与内存管理（中）](http://www.cocoachina.com/ios/20150922/13383.html)
* [说说iOS与内存管理（下）](http://www.molotang.com/articles/2073.html)

