**On Main Memory**
Discuss how memory is organised (a series of locations, each a set size and identified by an address,  in software identified by a variable name). Discuss how memory can traverse multiple locations. Common data structure sizes. How to find the size of a data type. Strings and their endings. Virtual memory vs Physical memory. How address space works.

Follow up: Discuss the different address types and how they work in assembly.

**cpp inline functions**
Declaring a function inline substitutes the code everywhere the function is called for better perfomance at the cost of greater size.

**cpp templates**
Usually a class acts on specific types. Templates allow classes to be declared that can act on multiple types. It is up to the person using the class to ensure that the template can be applied correctly. template <class a_type>

**stack**
A stack is aptly named, it implies a list of things which can be visualized as one placed on the other, like a stack of plates or boxes. A stack enforces that the last item in is the first item out (Last In, First Out). There are many real world examples where a stack is appropriate, for example in an undo-redo list. The first action you want to undo is the last item you did. Adding an item to the stack is called pushing an item onto the stack, removing an item from the stack is called popping an item from the stack. Some stacks also implement a "peek", which allows you to view the last item added to the stack without removing it from the stack.

**what is assert.h?**

**Git branch and merge**
tags:git
http://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging
git branch b_name
git checkout b_name

OR you can do both at once:
git checkout -b b_name
