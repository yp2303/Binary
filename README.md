# Binary

 Write a program to use strcat() function
Source Code:
#include <stdio.h>
#include <string.h>
 
int main( )
{
   char source[ ] = "strcat()" ;
   char target[ ]= " Program in C " ;
 
   printf ( "\nSource string = %s", source ) ;
   printf ( "\nTarget string = %s", target ) ;
 
   strcat ( target, source ) ;
 
   printf ( "\nTarget string after strcat( ) = %s \n", target ) ;
}
