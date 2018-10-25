# WinFlexBison
A useful tool to compile the lex&amp;yacc files into cpp files( based on visual studio ) on the Windows platform

The ppt show how to add command in visual studio to compile the .l .y files

Command Line:

win_flex --wincompat  -o %(Filename).cpp  %(Identity)

Outputs:  

%(Filename).cpp

Additional Dependencies: 

parser.y


Command Line: 

win_bison -o %(Filename).cpp %(Identity)

Outputs:
			
%(Filename).cpp ; %(Filename).h
