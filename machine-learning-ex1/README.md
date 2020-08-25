### computeCost.m

The total size of data X is 97 _ 2
So the cost function in the end, we should get 97 _ 1

```
h(97*1) = X(91*2) * thata(2*1)
```

Then according to the formula of J(theta):

```
J = (1/(2*m)) * sum((h-y).^2);
```

[Ref video](https://www.youtube.com/watch?v=QHpKxM5Bho0)

### gradientDescent.m

Already know that cost function h:

```
h = X * theta
```

According to the formula:

h: 97 _ 1
y: 97 _ 1
X: 97 \* 2

we can do: `(h-y)`, because they are both 97*1
but, we cannot do
`(h-y)*X`. Since in the end, the whole formula should get a number as result, for all j then it is (1\*j)

```
H(1*97) = (h-y)'
theta = theta - a/m * H(1*97) * X(97*2)
```

[Ref video](https://www.youtube.com/watch?v=GrCt09z3EsI)
