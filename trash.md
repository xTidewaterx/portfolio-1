methods of aligning cards horizontally::

display: grid;

grid-template-columns: repeat(3, 1fr);

grid-auto-rows: auto;








methods of aligning cards horizontally::

.app__cardContainer {
    display: flex;
    justify-content: space-between;

  
}






    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    //we now have auto fit and repeat minMax