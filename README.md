TASK ONE
NUMBERS AND VARIABLES

1. Create three variables in a single line and assign values to them in such a manner that each one of
them belongs to a different data type.

>>> a,b,c=1,2.01,'string'
>>> print(type(a))
<type 'int'>
>>> print(type(b))
<type 'float'>
>>> print(type(c))
<type 'str'>
>>> 

2. Create a variable of type complex and swap it with another variable of type integer.

>>> x=10j
>>> y=20
>>> x,y=y,x


3. Swap two numbers using a third variable and do the same task without using any third variable.


4. Write a program that takes input from the user and prints it using both Python 2.x and Python 3.x Version. Not sure


5. Write a program to complete the task given below:
Ask users to enter any 2 numbers in between 1-10 , add the two numbers and keep the sum in
another variable called z. Add 30 to z and store the output in variable result and print result as the final output.

x=eval(input('Enter the value of your choice'))
Enter the value of your choice 10
>>> y=eval(input('Enter the value of your choice'))
Enter the value of your choice 20
>>> z=x+y Not sure

6. Write a program to check the data type of the entered values.
HINT: Printed output should say - The data type of the input value is : int/float/string/etc

>>> print(type(x))
<class 'int'>
>>> y=12.344
>>> print(type(y))
<class 'float'>
>>> z="tom"
>>> print(type(z))
<class 'str'>
>>>

7. Create Variables using formats such as Upper CamelCase, Lower CamelCase, SnakeCase and
UPPERCASE.
(Refer: https://capitalizemytitle.com/camel-case/)

hiMyNameIsYash
HiMyNameIsYash
hi_my_name_is_yash

8. If one data type value is assigned to ‘a’ variable and then a different data type value is assigned to ‘a’
again. Will it change the value? If Yes then Why?

Yes it will change. Because if we do not save it then it will keep on changing as and when we give any value to “a” 


TASK TWO
OPERATORS AND DECISION-MAKING STATEMENT

1. Write a program in Python to perform the following operation:
If a number is divisible by 3 it should print “Consultadd” as a string
If a number is divisible by 5 it should print “Python Training” as a string
If a number is divisible by both 3 and 5 it should print “Consultadd - Python Training” as a string.

x=int(input("Enter the number:"))
if ((x%3==0) & (x%==5)):
    print("Consultadd-Python Training")
elif (x%3==0):
    print("Consultadd")
elif (x%==5):
    else print("Invalid number")

2. Write a program in Python to perform the following operator-based task:
3. num1= int(input('enter the number of your choice'))
4. num2= int(input('enter the number of your choice'))
3. Write a program in Python to implement the given flowchart:
a=10
b=20
c=30
avg=(a+b+c) / 3 
print("avg = ", avg)
if avg>a and avg >b:
    print("avg is higher than a,b")
    elif avg > a and avg > c:
        print ("avg is higher than a,c")
        elif avg > b and avg avg > c:
            print("avg is higher that b,c")
            elif avg > a:
                print("avg is just higher than a")
                elif avg > b:
                    print("avg  is higher than just b")
                    else:
                        print("avg is higher than just c")

             4. Write a program in Python to break and continue if the following cases occurs:
If user enters a negative number just break the loop and print “It’s Over”
If user enters a positive number just continue in the loop and print “Good Going”

x=int(input('enter a value'))
if x<0:
    print('it's over)
    break

5. Write a program in Python which will find all such numbers which are divisible by 7 but are not a multiple of 5, between 2000 and 3200.
var=[]
for x in range(2000, 3201):
    if (x%7==0):
        var.append(str(x))
print (','.join(var))

6.What is the output of the following code examples?
* Invalid syntax error

i = 0
while i < 5 :
    print(i)
    i += 1
    if i == 3 :
        break
    else:
        print("error")


NameError: name 'true' is not defined

7. Write a program that prints all the numbers from 0 to 6 except 3 and 6.
Expected output: 0 1 2 4 5
Note: Use ‘continue’ statement

for x in range (6):
    if (x==3 or x==6):
        continue
    print(x,end=' ')
    print("\n")




8. Write a program that accepts a string as an input from the user and calculate the number of digits
and letters.
Sample input: consul72
Expected output: Letters 6 Digits 2

var = input("Input a string")
d=l=0
for i in var:
    if i.isdigit():
        d=d+1
    elif i.isalpha():
        l=l+1
    else:
        pass
print("Letters", l)
print("Digits", d)  

9.Read the two parts of the question below:
Write a program such that it asks users to “guess the lucky number”. If the correct number is
guessed the program stops, otherwise it continues forever.

number = input("Guess the lucky number ")
while number = 5:
    print ("That is not the lucky number")
    number = input("Guess the lucky number ")

Modify the program so that it asks users whether they want to guess again each time. Use two
variables, ‘number’ for the number and ‘answer’ for the answer to the question whether they want
to continue guessing. The program stops if the user guesses the correct number or answers “no”. (
The program continues as long as a user has not answered “no” and has not guessed the correct
number)

number = 1
      again = "yes"
      while number != 5 and again != "no":
        number = input("Guess the lucky number: ")
        if number != 5:
          print ("That is not the lucky number")
          again = raw_input("Would you like to guess again? ")


10.Write a program that asks five times to guess the lucky number. Use a while loop and a counter,
such as
counter=1
While counter <= 5:
print(“Type in the”, counter, “number”
counter=counter+1
The program asks for five guesses (no matter whether the correct number was guessed or not). If the
correct number is guessed, the program outputs “Good guess!”, otherwise it outputs “Try again!”.
After the fifth guess it stops and prints “Game over!”.

counter = 1
      while counter <= 5:
        number = input("Guess the " + str(counter) + ". number ")
        if number != 5:
          print "Try again."
        else:
          print "Good guess!"
        counter = counter +1
      else:
        print "Game over"

11. In the previous question, insert break after the “Good guess!” print statement. break will terminate
the while loop so that users do not have to continue guessing after they found the number. If the user
does not guess the number at all, print “Sorry but that was not very successful”.

counter = 1
      while counter <= 5:
        number = input("Guess the " + str(counter) + ". number ")
        if number != 5:
          print "Try again."
        else:
          print ("Good guess!")
          break
        counter = counter +1
      else:
        print ("Sorry but that was not very successful")


