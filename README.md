# Trees: Solving problems with trees

To succeed at this challenge, you'll need to demonstrate that you can do the following:

- Solve various problems with trees.

> *Note: If downloading the assessment files to your local machine, make sure you're running Node v18 before you run* `npm install`.
>
> 1.  *Check which version you are running:* `node -v`
> 2.  *If needed, change the version to v18:* `nvm use v18`
>
> _For additional help, review the "Learn your tools: Visual Studio Code" lesson in the "Welcome" module._

## Instructions

Your goal for this assessment is to get the tests to pass.

To do so, you will be modifying the existing `BinarySearchTree` class to add methods that traverse the BST using in-order, pre-order, and post-order traversals.

### Existing files

| File path                 | Description                                                                                                                                                        |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `src/BinarySearchTree.js` | Contains the definition of the `BinarySearchTree` class. The `constructor()` method and methods from the previous assessments have already been completed for you. |

### Tasks

Complete the following tasks to pass the tests and this assessment.

In `src/BinarySearchTree.js`:

1.  Count leaves: Write a method to count the number of leaves in the tree. Your method should return a number as an output. If the tree only has a single node, return `1`. Add your solution to the `countLeaves()` method.

2.  Balanced BST: Write an algorithm that checks if a BST is height-balanced (i.e., the height of the left subtree differs from the height of the right subtree by no more than 1), returning the height of the BST if it is balanced, or `-1` otherwise. Add your solution to the `isBalancedBST()` method.

Once these tasks are complete, all tests should pass.
