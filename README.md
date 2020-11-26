# Ex1oop


This is an object oriented programmin project which his main idea is based on functions.

This Project Made by Yosef Desse Student in Ariel University.

at this project we implement the data structure of undirectional weighted graph with vertexs and edges. 

we implement a 2 class: WGraph_DS , WGraph_Algo and These classes  contains serval methods.



Class WGraph_DS:

This class represents the set of opretions applicable on graph in  a undirectional weighted graph.
 This class has inner class. 

 node_info class :
 
This inner Class represents the set of operations applicable on a  single node(vertex) in a undirectional weighted graph. Every node gets it key, tag and info.

node_data getNode(int key):

return  node by given key.

boolean hasEdge(int node1, int node2):

check if there is an edge between node1 and node2.

double getEdge(int node1, int node2):

return the Weight of the edge between node1 and node2 If and there is ,else return -1.

void addNode(int key):

add a new node to the graph. 

voide connect(int node1, int node2): 

add an edge between node1 and node2. If and there is already edge exists between node1 and node2 just update the Weight

getV():

return all the vertice in the graph

getV(int node_id):

return all the neighbors of the given node

node_data removeNode(int key) :

delete the given node from the graph and delete him from all his neighbors (edges).

void removeEdge(int node1, int node2):

remove the edge between node1 and node2.

int nodeSize():

return the number of the nodes in the graph.

int edgeSize():

return the number of the edges in the graph.



Class WGraph_Algo:

This Class represents the "regular" Graph Theory algorithms.


boolean isConnected():

check if every there is a valid path from every node to the others.

int shortestPathDist(int src, int dest):

return the length of the shortest path between src to dest.

List<node_data> shortestPath(int src, int dest):

return the the shortest path between src to dest  as an list of nodes.

boolean save(String file):

saves the graph to the given file name.

boolean load(String file):

 load a graph from the file to this graph algorithm.
