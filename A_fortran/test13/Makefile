all:
	gfortran -c test13F.f
	gcc -c test13C.c
	gfortran -o result.out test13F.o test13C.o
	rm -rf *.o

clean :
	rm -rf *.out *~ *.bak *.o
