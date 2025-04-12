# CPS-Assignment

1) Time Complexity is O(nlogn)
This is because, in the outer loop, it runs n/2 times. As ½ is a constant, we omit it and the time complexity for the outer loop is O(n). In the inner loop, ‘j’ doubles every iteration until it reaches n. So it runs for log2(n) times. We remove the constant and so it is O(log(n)), and the overall time complexity is O(nlogn).


2) Time Complexity is O((x)½ )
This is because the loop ends when i*i becomes greater than x. It begins with i = 1 and it runs until i is just greater than x^(½).


How I solved the coding problem:
To solve this coding problem, I created two points at the two lines between which I calculated the area. Throughout the loop, I calculated the area and everytime the area was greater than the maxArea, I replaced maxArea with that area. To find out the area, I calculated the height and width using corresponding points of the lines.



