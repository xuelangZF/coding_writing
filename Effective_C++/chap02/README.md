# 第二章 变量和基本类型
数据类型是程序的基础，告诉我们能在数据上执行的操作，以及数据的意义。C++ 支持广泛的数据类型，包括内置类型、标准库定义的复杂数据类型，以及用户自定义类型。

## 2.1 基本内置类型
内置基本类型包括：

* 算术类型：
    * 整型： short, int, long, long long, bool, char...
    * 浮点型：float, double, long double
* 空类型：不对应具体的值，用于特定场合，比如函数不返回任何值时用`空类型` void *作为返回类型。

除了bool型和扩展的字符型外，其他整型可以划分为：带符号类型和无符号类型。

对象的类型定义了对象包含的数据范围和能参与的运算，当我们使用了一种类型而其实对象应该取另一类型时，程序会执行`自动类型转换`（当然不是所有的场合都能进行类型转换）。*[type_conversions.cpp]*

当一个算术表达式中既含有无符号数又有int值时，会将计算结果将转换为无符号类型。*[type_conversions.cpp]*

> 提示：切勿混用带符号数和无符号数。


## 2.2 变量
 

## 2.3 复合类型

## 2.4 const 限定符

## 2.5 处理类型

## 2.6 自定义数据结构
