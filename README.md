Download Link: https://assignmentchef.com/product/solved-comp1400-lab8-working-with-functions
<br>



<strong>Prime Factors: </strong>Any integer above 1 is either a Prime Number, or can be made by multiplying Prime Numbers together. For example:

<ul>

 <li>= 2 x 2 x 2 x 2 = (2^4)</li>

 <li>= (17^1)</li>

 <li>= 2 x 3 x 3 = (2^1) x (3^2)</li>

</ul>

After reading an integer number from the user, named num, and given the first prime number 2, your program logic will:

<ol>

 <li>Determine and display how many times this prime number will occur in After finding each prime number, the value of num should be updated by dividing num to the found prime number. For example, after looking for the first prime number of 2 in the input num of 12, num will change to 3 (12 / (2×2)).</li>

 <li>Then the program will determine what is the next prime number, and go back to step a.</li>

 <li>Steps a. and b. will continue until the value of num is equal to 1.</li>

</ol>

Note: Your program should implement at least the following 3 functions (procedures):




<ul>

 <li>readNum()to take a valid number (greater than 1) from the user. This function has no input and returns a valid integer number entered by the user.</li>

 <li>IsPrime(…) to check if a number is a prime. This function has one integer variable as an input, named prime, and a boolean variable as an output, named p_flag.</li>

 <li>findPrimeCount(…) to count the number of a given prime in the input number and display the result in the format of (prime^freq). This function has two integer variables of num and prime as an input and returns the updated num. For example, calling findPrimeCount(12,2)returns the updated number of 3. <strong>Hint</strong>: The attached “findPrimeCount.png” provides a solution for this function.</li>

</ul>




A Sample interaction is as follow:

<table width="0">

 <tbody>

  <tr>

   <td width="208"> Enter a valid number (&gt;1):</td>

   <td width="60"><u>18</u></td>

  </tr>

  <tr>

   <td width="208">  18 = 1 x (2^1) x (3^3)Enter a valid number (&gt;1):</td>

   <td width="60"> <u>0</u></td>

  </tr>

  <tr>

   <td width="208">  Invalid number.Enter a valid number (&gt;1):19 = 1 x (19^1)</td>

   <td width="60"> <u>19</u> </td>

  </tr>

 </tbody>

</table>




<strong>Part A: RAPTOR Exercise </strong>

<ol>

 <li>Understand more about RAPTOR by watching the video about <u>Creating</u> <u>Procedures/Functions</u>.</li>

 <li>Start RAPTOR and create the flowchart of Prime Factors.</li>

 <li>Save the flowchart to a file named “primeFactor.rap” in the working directory on the PC you are using.</li>

 <li>Demonstrate the primeFactor.rap file to GA/TAs and run with different input values.</li>

</ol>

<strong>Hint</strong>: The mode of your Raptor should be “Intermediate” to be able to add a procedure. <strong> </strong>

<strong> </strong>

<strong>Part B: C Programming Exercise </strong>

<ol>

 <li>Implement the algorithm as represented by “primeFactor.rap”, and write an equivalent C program that accomplishes what the flowchart does.</li>

 <li>Save your program to a file named “primeFactor.c” in the working directory on the PC you are using.</li>

 <li>Demonstrate the primeFactor.c file to GA/TAs and run with different input values.</li>

</ol>

<strong> </strong>

<strong>EVALUATION: </strong>

You need to show your GA/TA the complete programs at the end of this lab, or at the beginning of your next lab. The marks you will receive for this lab are made of two parts: Lab work marks 10 and attendance marks 5. <strong>Total 15 marks</strong>.

<strong>Lab Work Mark</strong>: Your C code will be evaluated based on your solutions for the problems based on the following scheme:

<ol>

 <li>Does the code run and meet specifications?

  <ul>

   <li>Is input adequate and input data type properly validated?</li>

   <li>Is processing adequate?</li>

   <li>Is output correct and adequate?</li>

   <li>Is the code compliable? Is the code run properly?</li>

  </ul></li>

 <li>Is the code properly commented?

  <ul>

   <li>Is the program title, programmer’s first and last name, and the date posted at the top in a multi-line comment?</li>

   <li>Is each significant step of the program properly commented?</li>

   <li>Are comments added to clarify details?</li>

   <li>Are comments clear, accurate, neatly formatted, and have no misspellings?</li>

  </ul></li>

 <li>Is the code properly formatted?

  <ul>

   <li>Are blocks of code indented according to their parent-child relationship?</li>

   <li>Do curly braces line up vertically?</li>

   <li>Is there an empty line between significant steps (blocks) of the program?</li>

   <li>Is the width of the code contained within a reasonable limit so that minimal horizontal scrolling is required (with 800 x 600 monitor resolution), and there is minimal linewrapping when printed?</li>

   <li>Is camel-case notation used for variable, e.g. employeeLastName?</li>

  </ul></li>

</ol>