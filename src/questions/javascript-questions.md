---
title: JavaScript Questions
layout: layouts/page.njk
permalink: /questions/javascript-questions/index.html
---

* Explain event delegation.[Ans](https://gomakethings.com/whats-the-difference-between-javascript-event-delegation-bubbling-and-capturing/#event-delegation)  [Check this too](https://www.tutorialspoint.com/what-is-event-bubbling-and-capturing-in-javascript#:~:text=With%20bubbling%2C%20the%20event%20is,propagated%20to%20the%20inner%20elements.)
* Explain how `this` works in JavaScript. [Ans](https://youtu.be/Pv9flm-80vM)
* Can you give an example of one of the ways that working with `this` has changed in ES6?
* Map, filter, reduce - [Ans](https://codeburst.io/map-filter-and-reduce-in-javascript-d2725c59571d) [Ans2](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce)
* Explain how prototypal inheritance works.
* Debouncing and throttling [Ans](https://www.telerik.com/blogs/debouncing-and-throttling-in-javascript) [Ans2](https://stackoverflow.com/questions/25991367/difference-between-throttling-and-debouncing-a-function)
* What's the difference between a variable that is: `null`, `undefined` or undeclared? [Ans](https://betterprogramming.pub/javascript-interviews-whats-the-difference-between-a-variable-that-s-null-undefined-or-cb1c8f41e6c3)
  * How would you go about checking for any of these states?
* What is a closure, and how/why would you use one? [Ans 1](https://stackoverflow.com/a/39045098/9961394) [Ans 2](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures)
* What language constructions do you use for iterating over object properties and array items?
* Can you describe the main difference between the `Array.forEach()` loop and `Array.map()` methods and why you would pick one versus the other? [Ans](https://www.freecodecamp.org/news/4-main-differences-between-foreach-and-map/)
* What's a typical use case for anonymous functions? [Ans](https://qr.ae/pN3aG5)
* What's the difference between host objects and native objects?
* Explain the difference between: `function Person(){}`, `var person = Person()`, and `var person = new Person()`?
* Explain the differences on the usage of `foo` between `function foo() {}` and `var foo = function() {}`[Ans](https://stackoverflow.com/a/336868/9961394)
* Can you explain what `Function.call` and `Function.apply` do? What's the notable difference between the two? [Ans](https://stackoverflow.com/a/52081193/9961394)
* Explain `Function.prototype.bind`.
* What's the difference between feature detection, feature inference, and using the UA string?
* Explain "hoisting".
* Describe event bubbling. [Ans](https://stackoverflow.com/a/4616720/9961394)
* Describe event capturing.
* What's the difference between an "attribute" and a "property"?
* What are the pros and cons of extending built-in JavaScript objects?
* What is the difference between `==` and `===`? [Ans](https://www.java67.com/2013/07/difference-between-equality-strict-vs-operator-in-JavaScript-Interview-Question.html#:~:text=In%20one%20word%2C%20main%20difference,variable%2C%20if%20two%20variables%20are)
* Explain the same-origin policy with regards to JavaScript.
* Why is it called a Ternary operator, what does the word "Ternary" indicate? [Ans](http://rlynjb.github.io/wandrr/JS-Interview-Question-Why-is-it-called-a-Ternary-expression-what-does-the-word-Ternary-indicate)
* What is strict mode? What are some of the advantages/disadvantages of using it?
* What are some of the advantages/disadvantages of writing JavaScript code in a language that compiles to JavaScript?
* What tools and techniques do you use debugging JavaScript code?
* Explain the difference between mutable and immutable objects.
  * What is an example of an immutable object in JavaScript?
  * What are the pros and cons of immutability?
  * How can you achieve immutability in your own code?
* Explain the difference between synchronous and asynchronous functions.
* What is event loop? [Ans](https://www.educative.io/edpresso/what-is-an-event-loop-in-javascript)
  * What is the difference between call stack and task queue? [Ans](https://stackoverflow.com/questions/33874419/difference-between-call-stack-and-task-queue#:~:text=So%20in%20short%2C%20a%20job,method%20from%20a%20call%20stack.)
* What are the differences between variables created using `let`, `var` or `const`? [Ans](https://www.freecodecamp.org/news/var-let-and-const-whats-the-difference/#:~:text=var%20declarations%20are%20globally%20scoped%20or%20function%20scoped%20while%20let,the%20top%20of%20their%20scope.)
* What are the differences between ES6 class and ES5 function constructors?
* Can you offer a use case for the new arrow `=>` function syntax? How does this new syntax differ from other functions?[Ans](https://www.youtube.com/watch?v=h33Srr5J9nY)
* What advantage is there for using the arrow syntax for a method in a constructor?
* What is the definition of a higher-order function?
* Can you give an example for destructuring an object or an array?
* Can you give an example of generating a string with ES6 Template Literals?
* Can you give an example of a curry function and why this syntax offers an advantage?
* What are the benefits of using `spread syntax` and how is it different from `rest syntax`? [Ans](https://javascript.info/rest-parameters-spread)
* How can you share code between files?
* Why you might want to create static class members?
* Where would you put your Javascript files? Would you use async or defer? If yes, when and how? [Ans](https://www.growingwiththeweb.com/2014/02/async-vs-defer-attributes.html#script)
* What is the difference between `while` and `do-while` loops in JavaScript?
* What is a promise? Where and how would you use promise?[Ans](https://javascript.info/promise-basics)

## Coding questions
* Make this work:
```javascript
duplicate([1,2,3,4,5]); // [1,2,3,4,5,1,2,3,4,5]
```
* Create a for loop that iterates up to `100` while outputting **"fizz"** at multiples of `3`, **"buzz"** at multiples of `5` and **"fizzbuzz"** at multiples of `3` and `5`
* What will be returned by each of these?
```javascript
console.log("hello" || "world")
console.log("foo" && "bar")
```
* Write an immediately invoked function expression (IIFE)
