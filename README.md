# 4-bit-full-adder

## System Design
We divide the system into four 1-bit full adder modules for this adder. The 4-bit adder design is contained in file `FullAdder4.bdf`, while the 1-bit full adder module is contained in file `FullAdder1.bdf`. 

## 4-bit Adder
### Design
![FullAdder4](https://github.com/yvesfhsu/4-bit-full-adder/assets/81082886/0d626a0c-7efc-428d-88d7-77702c5a07b9)

## 1-bit Full Adder Module
### Boolean Expression
Three inputs (A, B, and Ci for carry in) and two outputs (S for sum and Co for carry out) make up the full adder. 

S (sum) is implemented with XOR gate: 
$$\mathrm{S=A\oplus{}B\oplus{}C_i}$$

Co (carry out) is implemented by two-level AND-OR gate: 
$$\mathrm{AC_i+BC_i+AB}$$

### Design
![FullAdder1](https://github.com/yvesfhsu/4-bit-full-adder/assets/81082886/bac42484-6d1d-4aa3-beaa-56e270ce6e73)

## Waveform
![Waveform](https://github.com/yvesfhsu/4-bit-full-adder/assets/81082886/8442537b-a5d5-4727-bbee-74330444685d)
