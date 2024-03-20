# Secure-Password-Validation-Tool
This Python script utilizes two libraries:

Tkinter: Tkinter is the standard GUI (Graphical User Interface) toolkit for Python. It provides a set of tools for building graphical user interfaces in Python, allowing developers to create windows, buttons, entry fields, and other GUI elements. In this script, Tkinter is used to create a simple GUI window with an entry field for entering passwords and a button to trigger the password validation process.

bcrypt: Bcrypt is a password hashing library designed to securely hash passwords. It uses the Blowfish encryption algorithm with a configurable work factor, making it resistant to brute-force attacks. In this script, the bcrypt library is used to hash passwords and compare them against a pre-existing hash for validation. The bcrypt.checkpw() function is employed to compare the entered password with the pre-existing hash securely. If the password matches the hash, the script prints "Login Successful"; otherwise, it prints "Invalid Password".





