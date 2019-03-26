Toolchain=g++
Compile_Flag=-c
Execute_Flag=-o
all: hello
hello: C++_programme.o Subtraction.o Addition.o Division.o Multiplication.o
	$(Toolchain) C++_programme.o Subtraction.o Addition.o Division.o Multiplication.o $(Execute_Flag) hello
C++_programme.o: C++_programme.cpp
	$(Toolchain) $(Compile_Flag) C++_programme.cpp -g
Addition.o: Addition.cpp
	$(Toolchain) $(Compile_Flag) Addition.cpp -g
Subtraction.o: Subtraction.cpp
	$(Toolchain) $(Compile_Flag) Subtraction.cpp -g
Division.o: Division.cpp
	$(Toolchain) $(Compile_Flag) Division.cpp -g
Multiplication.o: Multiplication.cpp
	$(Toolchain) $(Compile_Flag) Multiplication.cpp -g
clean:
	rm -rf *o hello
