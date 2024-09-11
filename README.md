# Basic writing and formatting syntax

## How to Create a Headings?
To create a heading, add one to six `#` symbols before your heading text. The number of `#` will determine the hierarchy level and typeface size of the heading.
``` markdown
# A first-level heading
## A second-level heading
### A third-level heading
```

## How to Create a Table?
We can add three dashes (center aligned): | --- |
Center align with two dashes: | :---: |
Left align with two dashes: | :--- |
Right align with two dashes: | ---: |

For example: 
```markdown
| Attempt | #1 | #2 | #3 | #4 | #5 | #6 | #7 | #8 | #9 | #10 | #11 | #12 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Seconds | 301 | 283 | 290 | 286 | 289 | 285 | 287 | 287 | 272 | 276 | 269 | 254 |
```
| Attempt | #1 | #2 | #3 | #4 | #5 | #6 | #7 | #8 | #9 | #10 | #11 | #12 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Seconds | 301 | 283 | 290 | 286 | 289 | 285 | 287 | 287 | 272 | 276 | 269 | 254 |

## How to deal with Syntax highlighting?
<pre>
```python
def greeting():
  print ("Hello World!")
```
</pre>
```python
def greeting():
  print ("Hello World!")
```

# Writing mathematical expressions
## How to write Math Equations?
There are two options for delimiting a math expression inline with your text. You can either surround the expression with dollar symbols `($)`, or start the expression with `$` and end it with `$.` The latter syntax is useful when the expression you are writing contains characters that overlap with markdown syntax.

```This sentence uses `$` delimiters to show math inline:  $\sqrt{3x-1}+(1+x)^2$```

This sentence uses `$` delimiters to show math inline:  $\sqrt{3x-1}+(1+x)^2$

```This sentence uses $\` and \`$ delimiters to show math inline:  $`\sqrt{3x-1}+(1+x)^2`$```

This sentence uses $\` and \`$ delimiters to show math inline:  $`\sqrt{3x-1}+(1+x)^2`$

## Writing expressions as blocks
To add a math expression as a block, start a new line and delimit the expression with two dollar symbols `$$`.
```markdown
**The Cauchy-Schwarz Inequality**
$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$
```
**The Cauchy-Schwarz Inequality**
$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$

Alternatively, you can use the ```math code block syntax to display a math expression as a block. With this syntax, you don't need to use $$ delimiters. The following will render the same as above:
```markdown
**The Cauchy-Schwarz Inequality**

```math
\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)
```
```

	 	
