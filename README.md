# awesome-type-theory t : τ :: κ
A compilation of good resources I've found for learning type theory.

## τ | General

### Books
+ **Type Theory & Functional Programming** by Simon Thompson
  + [This is essential!](https://kar.kent.ac.uk/20998/1/ttfp.pdf)
 
### Articles

+ [How to make ad-hoc polymorphism less ad hoc](https://people.csail.mit.edu/dnj/teaching/6898/papers/wadler88.pdf) by Philip Wadler and Stephen Blott (1988)
  + The paper that introduced type classes to the world
  + However, as noted by the authors there was work prior to theirs that was scratching the same surface. Stefan Kaes introduced, a tad earlier than Wadler and Blott, a system of ad hoc overloading in his brief 14-page paper.
  + [Parametric overloading in polymorphic programming languages](https://link.springer.com/chapter/10.1007/3-540-19027-9_9) by Stefan Kaes (1988)
+ [A theory of qualified types](https://jgbm.github.io/eecs762f19/papers/jones.pdf) by Mark P. Jones
+ [Singleton Kinds and Singleton Types](https://www.cs.cmu.edu/~rwh/students/stone.pdf) by Christopher Allan Stone (2000)
+ 

### Blog posts

+ [Demystifying Types Classes](https://okmij.org/ftp/Computation/typeclass.html#Kaes)

## κ | Kinds

In essence, the type of a type. An order higher than the type, but resembles the relationship that types share with terms.

### Articles

+ [Kind Inference for Datatypes: Technical Supplelemnt](https://xnning.github.io/papers/kind-inference-technical-supplement.pdf) by Ningning Xie et al.
+ [Kind polymorphism - Glasgow Haskell Compiler User's Guide](https://ghc.gitlab.haskell.org/ghc/doc/users_guide/exts/poly_kinds.html)
+ [Exiplicitly-kinded quantification - Glasgow Haskell Compiler User's Guide](https://ghc.gitlab.haskell.org/ghc/doc/users_guide/exts/kind_signatures.html)

### Blog posts

+ [Haskell's kind system - a primer](https://diogocastro.com/blog/2018/10/17/haskells-kind-system-a-primer/) by Diogo Castro
+ [All you need is higher kinded types](https://las.rs/blog/all-you-need-is-hkt-s.html) by Las Safin
+ [It's a Kind of Magic: Kinds in Type Theory](https://dev.to/riccardo_cardin/its-a-kind-of-magic-kinds-in-type-theory-8ll) by Riccardo Cardin

### Code snippets

+ [Example of Kind inference using unification-base constraint solving.](https://gist.github.com/soupi/ee78682851f396dc9b1953e9a72b9085) by soupi
