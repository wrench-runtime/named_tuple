# named_tuple
Easy way to create data classes for wren

After an idea from @ChayimFriedman2

```wren
import "named_tuple" for NamedTuple

S = NamedTuple.create("S", ["x", "y"])
s = S.new(1, 2)
System.print(s) // S(1, 2)
System.print("(%(s.x, s.y))") // (1, 2)
```
