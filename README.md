# ES6 Practice Questions

** Solve the following questions for your practice:**

Question 1: Declare a variable called `age` with a value `20` and see if you are able to update the value to `22`. Use appropriate variable declaration method and see if you are able to print the expected output to the console.

Expected Console Output:
Program 1:
Original age: 20
Updated age: 22

Question 2: Declare two variables, `num1` with a value `20` and `num2` with a value `5`. Calculate the product and difference of two values and print to the console. Use appropriate variable declaration method and see if you are able to print the expected output to the console.

Expected Console Output:
Program 2:
Product of num1 and num2: 100
Difference between num1 and num2: 15

Question 3: Declare a variable called `numberOfGates` with a value `5`. `numberOfGates` is a constant value and you should not be able to update it. Try to update the value to `6` and see what happens. Use appropriate variable declaration method such that you cannot update its value. Print the value to the console.

Question 4: Declare an object named `person` with two properties `name` and `age`. Modify the `age` property of the `person` object and update its value to `31`. Use appropriate variable declaration method and see if you are able to print the expected output to the console.

Expected Console Output:
Program 4:
Original person: { name: 'John', age: 30 }
Updated person: { name: 'John', age: 31 }

Question 5: Declare an object named `colors`. Add a property `tertiary` to it and print to the console. Use appropriate variable declaration method.

Expected Console Output:
Program 5:
Original Object: { primary: "red", secondary: "blue" }
Updated Object: { primary: "red", secondary: "blue", tertiary: "green" }

Question 6: What will be the output of the following code?

  const numbers = [1, 2, 3, 4]
  numbers[2] = 99
  console.log(numbers)

Question 7: What will be the output of the following code?

  const coordinates = { x: 10, y: 20 }
  console.log(coordinates)
  const newCoordinates = { x: 30, y: 40 }
  coordinates = newCoordinates
Question 8: What will be the output of the following code?

  let obj = { a: 1, b: 2 }
  const obj2 = { a: 3, b: 4 }
  obj = obj2
  console.log(obj)
  console.log(obj2)
Question 9: What will be the output of the following code?

  const numericVar = 2
  numericVar = 3
Question 10: What will be the output of the following code?

  const greeting = "Hello"
  console.log(greeting)
  let name = " Jay"
  name = " Shawn"
  console.log(greeting + name)

  Solve the following questions in a node JS REPL and submit the REPL link.

1. Write a program to increment age by 1 if birthday.

  const isBirthday = true;
  // your code here


  console.log("Program 1:");
  console.log(`Current Age: ${age}`);
  console.log("\n");


2. The condition has been written to print the message. Declare all the necessary variables needed and calculate ticket price based on age. Use appropriate declarations. If the passenger age is greater than 60, then there is a 15% discount on the ticket price.

// your code here


  if (passengerAge > 60) {
    console.log(`Ticket price for age greater than 60: ${discountedPrice}`);
  } else {
    console.log(`Ticket price for age less than or equal to 60: ${ticketPrice}`);
  }
  console.log("\n");


3. Declare three variables, `num1`, `num2`, and `num3` and write a program to find out if the third number is the largest. Print appropriate message as per the values taken.

Output for question 1, 2, and 3:



4. Define four items (Saree, Kurta, Jeans, Shoes) and their respective prices in a shopping cart. Use appropriate variable declarations. Calculate the total cart price by summing up the individual prices of all items.

Determine the delivery charge status based on the total cart price. If the total cart price is less than 1999, set an optional delivery charge of 99 and update the total cart price accordingly. If the total cart price is 1999 or more, indicate "No Delivery Charge" in the delivery charge status. Finally print the Shopping Cart with Optional Delivery Charge.

Output for question 4:



5. Declare appropriate variable and write code to check if a number is positive or negative.

If the number is greater than zero, print a message indicating that the number is positive.
If the number is less than zero, print a message indicating that the number is negative.
If the number is exactly zero, print a message indicating that the number is zero.


6. Find the students with the highest marks. Declare three variables `marks1`, `marks2`, and `marks3` to represent the marks of three students. Assign them the values `85`, `90`, and `78`, respectively. Declare three variables for student names `student1`, `student2`, and `student3`. Assign them the values `Rahul`, `Priya`, and `Tina`, respectively.

If `student1` has the highest marks, print a message to the console indicating that student 1 has the highest marks, in the following format: "Rahul has the highest marks: {marks1}". Print a similar message if any other student has the highest marks.
Output for question 5 and 6:

1. Create a function called `calculateSalary` that takes two arguments called `hoursWorked` and `hourlyRate`. Inside the function, calculate the total salary. Return the salary. Call the function with two arguments and `console.log` the result.


2. Create a function called `calculateBonus` that takes three arguments called `workedHours`, `marks`, and `salary`. Use appropriate variable declarations. Inside the function, check the eligibility for a bonus based on the following criteria:

- If `workedHours` is greater than 25 and `marks` is greater than 85, calculate a 10% bonus on the `salary` and return the updated salary.

- If `workedHours` is greater than 15 and `marks` is greater than 75, calculate a 5% bonus on the `salary` and return the updated salary.

- If none of the above conditions are met, return the `salary` without any bonus.

// code to call the function
console.log(calculateBonus(20, 80, 5000));


3. Create a function called `calculateFinalAmount` that calculates the final amount of a cart. The function takes four arguments called `price1`, `quantity1`, `price

4. 4. Create a function called `calculateAllowance` that takes three arguments: `age`, `isStudent`, and `baseAllowance`. Inside the function, determine the additional allowance based on the following criteria:

- If `age` is less than 18 and `isStudent` is true, add `100` to the `baseAllowance` and return the updated allowance.
- If `age` is between 18 and 25 (inclusive of both 18 and 25) and `isStudent` is true, add `50` to the `baseAllowance` and return the updated allowance.
- If none of the above conditions are met, return the original `baseAllowance`.
Call the function with three arguments (`age` as `16`, `isStudent` as `true`, and `baseAllowance` as `500`). Print the final output. Use appropriate variable declarations.

5. Create a function called `calculateShippingCost` that takes three arguments: `totalWeight`, `country`, and `baseCost`. Inside the function, calculate the shipping cost based on the following criteria:

- If `totalWeight` is less than or equal to `1 kg` and `country` is "Local", add `10` to the `baseCost` and return the updated cost.
- If `totalWeight` is greater than `1 kg` and `country` is "International", add `20` to the `baseCost` and return the updated cost.
- If none of the above conditions are met, return the `baseCost` without any additional charges.
Call the function with three arguments (`total weight` as `0.5`, `country` as “Local”, and `base cost` as `50`). Print the final output. Use appropriate variable declarations.

1. Write a function that prints the given array.

2. Write a function that returns a new array with `10` added to each number. Use for-loops. Print the result.

3. Write a function to convert all odd numbers in the array to the nearest even number by adding `1` to them. Print the result.

4. From the given array, create a new array with numbers divisible by `2`. Print the new array.

5. Write a function to print the sum of all numbers in the array.

6. Write a function to print the sum of odd numbers and sum of all even numbers in the given array.

Solve the following questions in a nodejs REPL and make your submission.

Question 1. Define an object 'car' with two properties, `brand` and `model`.

  1.1 Console the `brand` property of the `car` object.

  1.2 Console the `model` property of the `car` object.

  1.3 Change the value of `brand` property of the `car` object to "Honda".

  1.4 Console the updated `car` object.

  1.5 Add two more properties to the `car` object, `year` and `color`. Assign the value for `year` as `2022` and value for `color` as “Blue”.

  1.6 Use for-in loop to print all properties of the `car` object.

Question 2. Define an object 'citizen' with three properties, `name`, `age`, and `occupation`.

  2.1 Change the `age` property of the `citizen` object to `68` and print age to the console.

  2.2 Add `2` to the `age` property of the `citizen` object and print the age to the console.

  2.3 Add a property `city` to the object with value “Delhi” and then print all properties of the `citizen` object using for-in loop.

Question 3: Create a person object with properties `name` and `age`. Put your own value.

  3.1 Add a property '`bp`' to the person object with value "Normal".

  3.2 Check `age` and `bp` for fitness to travel. If the `age` of the person is above `60` and the `bp` is normal, then console "Fit to travel." otherwise console "Not fit to travel."

Output should be as per your object values.  

Solve the following questions in a nodejs REPL and make your submission.


Question 1: Given data for some students.

| name  | rollNo | hindi | english | maths |
|-------|--------|-------|---------|-------|
| Rahul | 101    | 80    | 75      | 90    |
| Amit  | 102    | 85    | 70      | 95    |
| Priya | 103    | 78    | 92      | 87    |

Convert the table into an array of objects.

Add marks for computers for each student respectively.

```javascript
const marksForComputer = [88, 92, 95]
1.1 Print the `studentsData` using for loops.

Expected output for 1.1:


1.2 Add marks for one more subject, science. Then print the updated `studentsData` with Science marks.

```javascript
const marksForScience = [82, 90, 88]
Expected output for 1.2:

Question 2: Another student Kaveri joins the class. Add Kaveri's data to studentsData.

Kaveri 104 84 88 78 90 86

2.1 Convert Kaveri's data to an object and print it.

2.2 Add Kaveri's data to studentsData. Then print the updated studentsData with Kaveri's data.

Expected output for 2.1 and 2.2:

2.3 Add a field totalMarks to every object in the array. Then print the updated studentsData with totalMarks.

2.4 Calculate the average marks and add avgMarks to each object. Then print the updated studentsData with avgMarks.

Expected output for 2.3 and 2.4:

Question 3: Write a function to calculate the grade for each student. Grade conditions have been provided below.

Condition	Grade
If avgMarks is from 90 to 100	A
If avgMarks is from 80 to 89	B
If avgMarks is from 70 to79	C
If avgMarks is from 60 to 69	D
If avgMarks is from 50 to 59	E
If avgMarks is below 50	F
Print report cards for each student.
