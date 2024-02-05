# Custom SMD Adapters

This project contains small PCBs that allow to solder SMD components on through hole project boards. They are similar to boards that can be found on Aliexpress and other sources but have the following advantages:

* The IC and the pins are oriented in the same direction and same order, making it easier to find a pin or IC pad of a given number.
* There are no spare pins. For example, a SOT23-5 adapter has exactly 5 pins, eliminating the need to skip pin numbers.
* They can be ordered from PCB houses for for significantly lower cost. For example a 5 boards with 30 adapters each, can be ordered from JLCPCB for less that $4 shipped.
* The PCBs can easly cut with scisors, without having to pay for a V-score option. We order 0.8mm PCBs and cut them with regular scisors.
* You can easily customize the adapters as needed, for example, adding pads for bypass capacitors. 
* You can pick your color of choise. We ordered black PCBs.

Front view
![Front view](kicad/smd_adapter.png)

Rear view
![Rear view](kicad/smd_adapter_rear.png)

---

# FAQ

Q: How can I create my own board with SMD adapters?

A: The SMD adapters are provided also as Kicad footprints. Simply create a Kicad project, create an empty PCB layout (no need to create a schema), and import the footprints you like.

---

Q: Why no V-Score lines?

A: It reduces the cost of ordering the PCBs.

---

Q: How do you cut the boards?

A: With regular scisors. When ordering, prefer thinner board such as 0.8mm over the more common 1.6mm. This will make the cutting easier.

---

Q: Where can I order these boards?

A: From your prefered PCB manufacturer. We have good experience with JLCPCB and are able to order 5 boards for less than $4 shipped.  (Sart your order with an empty cart and select the least expensive shipping method)

---





