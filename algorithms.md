## Depth First Search
Typically a graph problem. A tree structure, going through the trees. <br />

e.g. a string and searchin through characters. Transform something into a tree and search. <br />

e.g. Start at a starting point, go to the end, go back to the beginning, go through another tree. <br />

<p>MIT OpenCourseware, Intro to Algorithms, Lecture 14:</p>
<code>https://www.youtube.com/watch?v=AfSk24UTFS8</code>

<p>IIT Indian Institute of Technology, DFS</p>
<code>https://www.youtube.com/watch?v=iaBEKo5sM7w</code>

## Breadth First Search
BFS vs DFS: DFS adds nodes to a stack and takes last child off the top and visits its children, etc. BFS does the opposite. BFS uses a queue that adds child nodes, grab first one added, add the first one added and add all its children to the end of the queue.

<p>MIT OpenCourseware, Intro to Algorithms, Lecture 13:</p>
<code>https://www.youtube.com/watch?v=s-CYnVz-uh4</code>

## Matching Bracket Problem
Given a bunch of brackets, find if the string of brackets is valid or find the next valid bracket to add. <br />

Solution: Typically to use a stack where you add the last opening bracket to a stack and match whenever you find a closing bracket. <br />

## ** Hash Tables **
Given a 2D array. Traverse this and keep track of what you've already visited in a matrix. What datastructure is used? <br />

## Variables/Pointer Manipulation
A common need for algorithms. Traversing a string from Right to Left and Left to Right. Requires knowing manipulating multiple variables/pointers. <br />

Keeping track of a lot of variables in your head and tracking precisely. <br />

e.g. Find the longest palendromic substring in a string. Usually done by traversing the string. Every letter expand two pointers that expand outwards. from this, determing if you are dealing with a palindrome. <br />

## *** Reverse Linked List *** (duplicates, removing duplicates) 
Typically uses 3 different pointers. <br />

## Sorting Fundamentals (quicksort, mergesort, bubblesort techniques, runtime of a sort, time space complexity)
Understanding sorting algorithms concepts and how quicksort mergesort is faster than bubblesort.) Knowing how your O(nlog(n)) affects your algorithm. Different sorts can make runtime of algorithms better or worse. <br />

## Recursion
Not necessarily practical, however it lends itself to understanding problem solving. Be familiar with how it works. Learn more with practice! <br />

## Custom Data Structures (O-Oriented Programming)
Knowing how to construct a suffix tree datastructure. capture a bunch of strings in a data structure, get the first letter of a string. How many strings have the second letter 't', put the third letter 'r'. Be able to construct a class that will solve the problem well. Constructing a class method instead of a main method.<br />

e.g. You have a gumball machine. It will give you a pill that will contain a color. Construct an object which can call a method to extract a random result.<br />

## *** BINARY SEARCH ***
Very fundamental. Say you have a sorted list of integers and want to find an integer. <br />

Time space complexity of binary search is O(log(n)). This is because you eliminate half, then eliminate another half, etc. Picking one number and setting it as a pivot and dividing by half. <br />

e.g. Find the crash version of an app. Using binary search to check each version of an app to find when it went from working to crashing <br /> 
