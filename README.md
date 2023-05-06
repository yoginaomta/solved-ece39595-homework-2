Download Link: https://assignmentchef.com/product/solved-ece39595-homework-2
<br>
Your first task is to write two other C++ classes that extend Vehicle. The first is HondaFit, and it defines the following functions that should be called virtually from Vehicle pointers:

<ul>

 <li>HondaFit(std::string _color): A constructor that takes a single std::string argument that is the color, and passes the std::string “Honda Fit” to the Vehicle superclass constructor.</li>

 <li>std::string getModel( ) that returns the model field.</li>

 <li>std::string getColor( ) that returns the color field.</li>

 <li>std::string getEngine( ) that returns “1.5L i-DSI 4 Cylinder”</li>

 <li>std::string getTransmission( ) that returns “manual”.</li>

 <li>int getNumPassengers( ) that returns 5.</li>

 <li>std::string getWarranty( ) that returns “3/36,000 + 5/60,000 Powertrain”.</li>

</ul>

The second is FordF350 and it defines the following functions that should also be called virtually from Vehicle pointers:

<ul>

 <li>FordF350(std::string _color): A constructor that takes a single std::string argument that is the color, and passes the std::string “Ford F350” to the Vehicle superclass constructor.</li>

 <li>std::string getModel( ) that returns the model field.</li>

 <li>std::string getColor( ) that returns the color field.</li>

 <li>std::string getEngine( ) that returns “7.3L V8</li>

 <li>std::string getTransmission( ) that returns “10 speed automatic”.</li>

 <li>int getNumPassengers( ) that returns 3.</li>

 <li>std::string getWarranty( ) that returns “3/36,000 + 5/60,000 Powertrain”.</li>

</ul>

Compile each of these and remove all syntax errors, etc., that might have crept in. Then compile it with main.cpp. You will likely notice an error in main.cpp that getWarranty( ) is not found. Fix Vehicle.java so that this error goes away. Add a comment to the top of main.cpp explaining what you did.

When there are no more compiler errors, run your program.  It should give output that looks like:

HondaFit built

Ford F350 built HondaFit built

Ford F350 built




HondaFit: color: white, engine: 1.5L i-DSI 4 Cylinder, transmission:

manual, setBelts: 5, warranty: 3/36,000 + 5/60,000 Powertrain




Ford F350: color: green, engine: 7.3L V8, transmission: 10 speed automatic, setBelts: 3, warranty: 3/36,000 + 5/60,000 Powertrain




HondaFit: color: red, engine: 1.5L i-DSI 4 Cylinder, transmission:

manual, setBelts: 5, warranty: 3/36,000 + 5/60,000 Powertrain




Ford F350: color: yellow, engine: 7.3L V8, transmission: 10 speed automatic, setBelts: 3, warranty: 3/36,000 + 5/60,000 Powertrain

I am not going to be extremely picky about spaces, etc.