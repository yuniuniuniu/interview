1、为什么需要声明？ （在这些函数调用的时候，编译器就能对他们进行准确性检查）

2、为什么说getchar是非格式化输入

3、如何编写一个空循环体

4、寄存器变量怎么保存和恢复

5、自动变量的初始化

6、怎么用stdarg.h头文件定义的宏来实现可变参数

7、结构体存储和其中成员有什么联系

8、实现伪随机数的原理

9、set_jmp和long_jmp





数组通过引用方式传递（传址）

scanf的返回值是它成功转换并存储于参数中的值的个数

gets会导致产生缓存溢出的问题（遇到换行语句才停止）

注释是被预处理器拿掉的

字符串常量的直接值是一个指针，因此不能把它赋值给一个字符数组

函数的形参不能声明为静态，因为实参在堆栈中传递给函数来支持递归

++a的结果是a的拷贝，不是变量本身

.>=操作符返回的是整型值，不是布尔值

在对指针间接访问前，要确保它们已被初始化

将整型直接赋值给指针变量是错误的

函数调用都传值调用，数组的话是传址（传的是指针的拷贝）

常量不能++

strlen返回的是size_t类型的数据，它是一个无符号数

联合变量可以被初始化，初始值必须是联合第一个成员的类型

malloc如果分配成功返回的是指向该内存的指针

内存泄漏：动态分配的内存不再需要使用后不释放

字符串常量出现在表达式中时，它的值是个指针常量

每次使用宏的时候，一份宏定义代码的拷贝插入到程序中

每个流都对应一个FILE结构