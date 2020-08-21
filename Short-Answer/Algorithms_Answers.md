#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) The while loop initializes with n^3, but inside the loop it has a runtime complexity of n^2, the way to calculate the overall runtime complexity is to divide the complexity of the loop by the terms within the loop, giving a runtime of O(n) from n^3/n^2.


b) There are two loops which each have a runtime complexity of O(n), but since they are nested, they must be multiplied for a total complexity of O(n^2).


c) This function is linear since it is called only once for each time it is recursed, giving it a runtime of O(n).

## Exercise II

To determine the number of eggs I can drop, one egg must break. If the number of eggs broken is one, then I must stop dropping eggs. It would be most realistic and convenient for me to start at the first floor, so starting at the first floor I would enter the floor and drop an egg. If the egg breaks, I stop.

In pseudocode, this would be:

# Continue climbing floors and dropping eggs while there are no broken eggs

# Start at floor one and drop an egg, if the egg does not break, increment floor and increment number of eggs dropped

# When an egg breaks, stop dropping eggs and stop climbing floors, the ration for eggs will be number of eggs dropped to one broken egg

# The runtime complexity of this code will be O(n), since it will utilize one loop
