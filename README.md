AIM

To implement Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

SOFTWARE REQUIRED: Quartus prime

THEORY

Encoder 8 To 3

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

image
<img width="479" height="385" alt="Screenshot 2025-12-12 200146" src="https://github.com/user-attachments/assets/0c809260-0a82-43d0-87ed-09e5601d705d" />

Truth Table
<img width="656" height="506" alt="Screenshot 2025-12-12 200203" src="https://github.com/user-attachments/assets/37bcf8f8-ef03-4a27-9ea5-23dfefaada1a" />


The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:
<img width="919" height="519" alt="Screenshot 2025-12-12 200217" src="https://github.com/user-attachments/assets/475ab715-dadb-4422-a5ba-5df57798dcce" />

Procedure

Create project in Quartus.

Write Verilog code for encoder.

Add file to project.

Compile the design.

Simulate and check outputs.

PROGRAM

Program for Encoder 8 To 3 in Dataflow Modelling and verify its truth table in quartus using Verilog programming.

Developed by:YUVASREE S

RegisterNumber:25014102

RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling

TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling

RESULT

thus we implement encoder 8 to 3 in dataflow modelling using verilog and validating their functionality using functionality table has been done using Quartus software.
