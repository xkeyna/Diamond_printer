# Diamond_printer
Write a function diamondPrinter(n,character,filled,fillCharacter) that, given an in- teger size n, prints a diamond shape, which may or may not be filled. Additionally, in the middle of the shape it prints “Lancaster University!”, to the maximum possible extent. For instance, a diamond shape with size 5, using asterisks, but filled with o, would be as follows:
       *
      *o*
     *Lan*
      *o*
       *
In detail, the function inputs are:

n: Size of the diamond shape, in number of rows. n must be an odd number. If n is even, then a shape of size n − 1 will be printed.

 character: Character to be used when printing the outline of the figure.

 filled: Defines whether the shape would be filled or not. True means that it must be filled, and False that it must not be filled.

 fillCharacter: Character to be used when printing the inside of the figure (if filled). Note that this input may not be specified if filled is False. That is, calls diamondPrinter(n,character,filled)arealsovalid. IffilledisTrue,butfillCharacter is not specified, then by default a minus sign (-) is going to be used. Note that if filled is False, then this input must be ignored.
