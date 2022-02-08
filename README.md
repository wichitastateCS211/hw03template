# Drawing Shapes
Write a program that prints shapes to the screen while observing certain restrictions.

## Requirements
- The program takes no input.
- **For each shape,** the following characters may only appear **once:**
  - `'#'`
  - `' '` (space)
  - `'\n'`
- Place two blank lines between each shape.
  - **NOTE:** The restriction above does not apply to this requirement. In other words, the blank
  lines are not counted as being "part of the shape."
- The program output must look *exactly* like that found in the sample run.
- **REMINDER:** Discussion of the problem is always acceptable; sharing code is considered academic
dishonesty.

## Sample Run
```
########
 ######
  ####
   ##
   
   
   #
  # #
 #   #
#     #
 #   #
  # #
   #


#     #
 #   #
  # #
   #
  # #
 #   #
#     #


#######
#     #
#     #
#     #
#######
```

## Hints
- Make a plan first, the code will write itself.
- What *exactly* needs to be printed to the screen?
- What should the overall structure of the code look like to draw a shape?
- For each shape, look for a pattern.
- Can I alter my counting to my benefit?
- The library `<cstdlib>` contains an absolute value function, `int std::abs(int)`

## Reminders
- Name your file *wsuid*\_hw03.cpp
- You are required to place a comment block at the top of the file. Refer to the Coding Guidelines
handout.
