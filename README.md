# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```
#include <stdio.h> 
#include <stdlib.h> 
#include <time.h> 
int main() { 
int i, n; 
srand(time(0)); 
printf("Enter how many pseudorandom numbers you want to generate: "); 
scanf("%d", &n); 
printf("Generating %d pseudorandom numbers between 0 and 99:\n", n); 
for (i = 0; i < n; i++) { 
int randomNumber = rand() % 100; 
printf("%d ", randomNumber); 
} 
printf("\n"); 
return 0; 
} 
```

# OUTPUT:
<img width="1392" height="692" alt="image" src="https://github.com/user-attachments/assets/c05084e0-3f8e-44d9-8175-5431b6a75fd0" />


# RESULT:
Implementation of Pseudorandom Number Generation Using Standard library is successful.
