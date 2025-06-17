# Case-Converter-Program

# 🐍 Pascal/Camel Case to Snake Case Converter

This simple Python script converts a PascalCase or camelCase string to `snake_case`.

## 💡 Example

```python
>>> convert_to_snake_case("IAmAPascalCasedString")
'i_am_a_pascal_cased_string'


.
├── convert_to_snake_case.py
└── README.md


How It Works
The convert_to_snake_case function iterates through each character of the input string. If the character is uppercase, it adds an underscore _ followed by the lowercase version of that character. Finally, it joins the characters together and strips any leading or trailing underscores.

 Getting Started
Requirements
Python 3.x

Running the Script
Clone the repository:
git clone https://github.com/yourusername/snake-case-converter.git
cd snake-case-converter
Run the script:

bash
Copy code
python convert_to_snake_case.py

Function Definition
python
Copy code
def convert_to_snake_case(pascal_or_camel_cased_string):
    snake_cased_char_list = [
        '_' + char.lower() if char.isupper()
        else char
        for char in pascal_or_camel_cased_string
    ]
    return ''.join(snake_cased_char_list).strip('_')
📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🙌 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you'd like to change.

Happy Coding! 💻









