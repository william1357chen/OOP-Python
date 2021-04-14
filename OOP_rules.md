# General Rules of OOP
1. All user classes are mutable

1. Passing `self` in every regular method. if you want a class method, use `@classmethod` decorator and pass in `cls`. If you want a static method, use `@staticmethod` decorator.

1. `ClassObject.method() == ClassName.method(ClassObject)`

1. Class variables can be accessed with `ClassName.VariableName`

1. `super().__init__()` is the syntax for calling the base class's constructor

1. '@property' for Getter, '@methodname.setter' for Setter, and `@methodname.deleter` for Deleters