CC := g++ -std=c++11

chaff: solver.o
	$(CC) -O3 -o $@ $^

%.o: %.cpp
	$(CC) -c -O3 -o $@ $<