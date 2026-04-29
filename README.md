# CE-ESY-assignments
# Circular Buffer in C

This project implements a Circular Buffer (Ring Buffer) using C language to store and read characters efficiently using FIFO (First In, First Out).

## Features:

* Initialize the buffer
* Write data into the buffer
* Read data from the buffer
* Handle Overflow (Buffer Full)
* Handle Underflow (Buffer Empty)
* Track `head`, `tail`, and `count`

## Methods:

### `initBuffer()`

Initializes the buffer by setting:

* `head = 0`
* `tail = 0`
* `count = 0`

### `writeBuffer()`

Adds a character to the buffer if space is available.
If the buffer is full, it displays an Overflow message.

### `readBuffer()`

Reads and removes a character from the buffer.
If the buffer is empty, it displays an Underflow message.

## Main Function:

* Takes user input (name)
* Appends `" CE-ESY"` to the input
* Stores the result in the circular buffer
* Reads and displays the stored data
* Verifies that the buffer is empty after reading




