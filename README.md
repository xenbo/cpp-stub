c++单元测试打桩接口
================
测试代码--->被测代码--->被测代码依赖库（无源码）


说明：
1. stub类用来打桩使用
2. private相关方法主要用来获取类的私有成员（主要针对无源码的依赖库内的接口打桩时使用）
3. 被测代码获取类的私有成员，使用-fno-access-control取消权限控制
4. 支持linux和windows下使用，示例主要针对linux，windows有所区别




