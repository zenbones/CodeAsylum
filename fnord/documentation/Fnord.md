Modules

A single file which contains Classes and Objects.

Class

value := <number> | "<string>" | '<character>'  | variable | function

unit := {expression...}

expression :=

​	var name = value or : type

​	const name = value or : type

​	def name ():type unit

​	variable = value

​	function

built in functions

​	if () {} else {}

​	switch () {case  pattern: unit| default: unit}

​	while () unit

​	do unit while ()

​	for (name: type in <iterable>) unit

​	try() unit catch () unit finally unit

​	break value

​	return value

Interface

built in interfaces

​	iterable

​	comparable

Permission Modifiers

​	Class

​		public

​		package

​		module <defult>

​		Fields or Methods

​			private <default>

​			public

​			protected (seen by subclasses)

​			package

​			module

​	Module

​		public

​		package <default>

​		