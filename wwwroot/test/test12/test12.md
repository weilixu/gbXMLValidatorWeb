# Test Case 12 – Concave Space
## Test Description:
Most space in buildings are rectangular, and they can be successfully exported into a gbXML model. However, sometimes designers design space in a concave shape, which means one of the inner angles is greater than 180 degree. These spaces could results issues in exported gbXML models. In this test case, software should successfully export a concave shape space to a gbXML model.
## Spaces / Rooms:
There is only one space in this test model. It is named as “level_1_space_1”. The space shape is the same as the building shape.
## Special Considerations:
1.	The model dimension is detailed in Figure 1.
2.	The exterior wall thickness is set to 8”.
3.	All the walls face to an orientation shall be named as: “[orientation]_wall_[custom index]”
4.	All the other surfaces shall be named as their function, such as “interior_wall_[custom index]”
5.	The custom index is an index to differentiate the same type surfaces. The tester can decide how to label the custom index.




## Description of Test Case:
### Figure 1. Isometric View
Shows a 3-dimensional isometric view of this test model. Walls locates between the slab floor and the roof.
### Figure 2. Floor and Ceiling Plan View
Shows a typical floor plan to indicate dimensions and directions of the space, with wall thickness, which are important for the gbXML space and surface definitions.  

### Figure 3. Section View
Shows the south elevation view to indicate positions and dimensions of the slab floor, roof or ceiling elements.