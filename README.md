# FdF
My FdF project for School21 by Sberbank

The task of the project is to write a program that draws a given map of heights, using the library minilibx. For more details see the file [sbj/10_fdf.en.pdf](https://github.com/TesenDesk/FdF/blob/master/sbj/10_fdf.en.pdf).

To start the program, first execute `make`.    
Use the command below to start the program.    
```
./fdf FILENAME
```
`FILENAME` - это файл с картой. Для удобства я добавил некоторые карты в папку `maps`.

__Please note__ For better performance, close the key assignment after starting the program with the `H` key.

The program opens in a new window and draws this map. You can change the viewing angle, distance between points by pressing the keyboard keys:    
`W, A, S, D` - change the viewing angle on x- and y-axes.    
Q, E - change the viewing angle on the z-axis.    
↑ ↓ ← →` - Move the map in the corresponding direction.    
`+, -` - Resize (zoom in/out) the map    
`Numpad1/Numpad3 ` - Change the distance along the x-axis.    
`Numpad4/Numpad6` - Change the distance on the y-axis.    
`Numpad7/Numpad9` - Change the distance on the z-axis.     
`Numpad0` - Reset distance to default.    
`Backspace` - Set the distance according to the size of the window.    
`Enter` - Set the position of the map to the center of the window.    
`Tab` - Return the standard viewing angle.    
`H` - Show/hide the purpose of the buttons.    
`Esc` - Close the window.

![img1](https://github.com/TesenDesk/FdF/blob/master/images/42-fdf.png)
![img2](https://github.com/TesenDesk/FdF/blob/master/images/france-fdf.png)
![img3](https://github.com/TesenDesk/FdF/blob/master/images/some_map-fdf.png)

I did this project together with a student of the School @jjerde. I did file validation and data saving. His part of the job was to write an algorithm to display the map and track keystrokes.

Final score: 125%

2019, Moscow, Russia
