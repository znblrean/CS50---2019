# CS50 2019 Solutions

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](https://www.python.org/)
[![C](https://img.shields.io/badge/C-99-orange)](https://en.wikipedia.org/wiki/C_(programming_language))
[![SQL](https://img.shields.io/badge/SQL-SQLite3-lightblue)](https://www.sqlite.org/)
[![HTML/CSS](https://img.shields.io/badge/HTML%2FCSS-5-green)](https://developer.mozilla.org/en-US/docs/Web)
[![Flask](https://img.shields.io/badge/Flask-2.3.0-red)](https://flask.palletsprojects.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Complete solutions and implementations for Harvard University's CS50 2019 course - Introduction to Computer Science. This repository contains all problem sets, labs, and final project solutions.

## Table of Contents
- [Course Overview](#course-overview)
- [Repository Structure](#repository-structure)
- [Problem Sets](#problem-sets)
- [Getting Started](#getting-started)
- [Usage Guidelines](#usage-guidelines)
- [Learning Path](#learning-path)
- [Contributing](#contributing)
- [Academic Integrity](#academic-integrity)

## Course Overview

CS50 is Harvard University's introduction to the intellectual enterprises of computer science and the art of programming. This repository contains solutions for the 2019 edition of the course, covering topics from basic programming to web development.

### Course Topics Covered
- **Week 0**: Scratch
- **Week 1**: C
- **Week 2**: Arrays
- **Week 3**: Algorithms
- **Week 4**: Memory
- **Week 5**: Data Structures
- **Week 6**: Python
- **Week 7**: SQL
- **Week 8**: HTML, CSS, JavaScript
- **Week 9**: Flask
- **Week 10**: Ethics
- **Final Project**: Capstone project

## Repository Structure

```
CS50---2019/
├── week0-scratch/          # Scratch programming projects
│   ├── hello/
│   └── project.sb3
│
├── week1-c/                # Introduction to C programming
│   ├── hello/             # Hello World in C
│   ├── mario/             # Mario pyramid problems
│   ├── cash/              # Greedy algorithm
│   └── credit/            # Credit card validation
│
├── week2-arrays/           # Arrays and strings in C
│   ├── caesar/            # Caesar cipher
│   ├── vigenere/          # Vigenère cipher
│   ├── crack/             # Password cracking
│   └── readability/       # Text readability analysis
│
├── week3-algorithms/       # Sorting and searching algorithms
│   ├── plurality/         # Plurality voting system
│   ├── runoff/           # Runoff voting system
│   └── tideman/          # Tideman voting algorithm
│
├── week4-memory/           # Memory management in C
│   ├── filter/           # Image filtering (blur, edges)
│   ├── recover/          # JPEG file recovery
│   └── volume/           # WAV file manipulation
│
├── week5-data-structures/  # Data structures implementation
│   ├── speller/          # Hash table implementation
│   ├── inheritance/      # Genetic inheritance simulation
│   └── dictionary/       # Dictionary implementation
│
├── week6-python/          # Python programming
│   ├── hello/           # Hello World in Python
│   ├── mario/           # Mario in Python
│   ├── cash/            # Cash problem in Python
│   ├── credit/          # Credit card in Python
│   ├── readability/     # Readability in Python
│   ├── dna/             # DNA sequence matching
│   └── sentiment/       # Sentiment analysis
│
├── week7-sql/            # Database and SQL
│   ├── movies/          # IMDB database queries
│   ├── houses/          # Student house database
│   └── finance/         # Stock trading simulation
│
├── week8-web/            # HTML, CSS, JavaScript
│   ├── homepage/        # Personal homepage
│   ├── trivia/          # Trivia game
│   └── birthdates/      # Birthday tracking
│
├── week9-flask/          # Web development with Flask
│   ├── hello/           # Flask hello world
│   ├── application/     # Flask application forms
│   ├── login/          # Login system
│   └── finance/        # Web-based finance app
│
├── week10-ethics/        # Ethics in computing
│   └── essays/          # Ethics essays and discussions
│
├── final-project/        # Final capstone project
│   ├── proposal/        # Project proposal
│   ├── implementation/  # Code implementation
│   └── documentation/   # Project documentation
│
├── labs/                 # Weekly lab exercises
│   ├── lab1/           # Hello, World variations
│   ├── lab2/           # Scrabble score calculator
│   ├── lab3/           # Sort and search algorithms
│   └── ...             # All weekly labs
│
├── practice-problems/    # Additional practice problems
│   ├── cash-practice/
│   ├── credit-practice/
│   └── mario-practice/
│
├── resources/           # Learning resources
│   ├── cheatsheets/    # Language cheatsheets
│   ├── templates/      # Code templates
│   └── references/     # Reference materials
│
├── docs/               # Documentation
│   ├── solutions/      # Solution explanations
│   ├── walkthroughs/   # Step-by-step guides
│   └── notes/          # Course notes
│
└── tests/              # Test files
    ├── unit-tests/     # Unit tests
    └── integration/    # Integration tests
```

## Problem Sets

### Week 0: Scratch
- **hello**: Basic Scratch program
- **project**: Interactive Scratch project
- **Topics**: Programming basics, events, loops, conditionals

### Week 1: C
- **hello**: "Hello, World!" program
- **mario**: Printing pyramids
- **cash**: Greedy algorithm for change
- **credit**: Luhn's algorithm for credit cards
- **Topics**: Variables, data types, operators, control flow

### Week 2: Arrays
- **caesar**: Caesar cipher implementation
- **vigenere**: Vigenère cipher implementation
- **crack**: Password cracking program
- **readability**: Coleman-Liau index calculator
- **Topics**: Arrays, strings, command-line arguments

### Week 3: Algorithms
- **plurality**: Simple voting system
- **runoff**: Ranked-choice voting
- **tideman**: Tideman voting algorithm
- **Topics**: Sorting algorithms, searching algorithms, recursion

### Week 4: Memory
- **filter**: Image filters (grayscale, sepia, reflection, edges)
- **recover**: JPEG file recovery from memory card
- **volume**: WAV file volume adjustment
- **Topics**: Pointers, memory allocation, file I/O

### Week 5: Data Structures
- **speller**: Spell checker with hash table
- **inheritance**: Blood type inheritance simulation
- **dictionary**: Dictionary implementation
- **Topics**: Linked lists, hash tables, tries, trees

### Week 6: Python
- **hello**: Python version of hello world
- **mario**: Mario pyramids in Python
- **cash**: Cash problem in Python
- **credit**: Credit card validation in Python
- **readability**: Readability calculator in Python
- **dna**: DNA sequence matching
- **sentiment**: Sentiment analysis
- **Topics**: Python syntax, lists, dictionaries, file I/O

### Week 7: SQL
- **movies**: IMDB database queries
- **houses**: Student database management
- **finance**: Stock trading web application
- **Topics**: SQL queries, database design, joins, indexes

### Week 8: Web
- **homepage**: Personal website
- **trivia**: Interactive trivia game
- **birthdates**: Birthday tracking application
- **Topics**: HTML, CSS, JavaScript, DOM manipulation

### Week 9: Flask
- **hello**: Basic Flask application
- **application**: Form handling with Flask
- **login**: Authentication system
- **finance**: Complete web application
- **Topics**: Web frameworks, routing, sessions, templates

### Week 10: Ethics
- **essays**: Ethics case studies and discussions
- **Topics**: Privacy, security, AI ethics, professional conduct

## Getting Started

### Prerequisites

1. **CS50 IDE** (Recommended)
   - Access via https://ide.cs50.io/
   - Or use local setup with CS50 library

2. **Local Development Setup**
   ```bash
   # Install CS50 library
   pip install cs50
   
   # For C programs
   sudo apt-get install gcc
   sudo apt-get install make
   
   # For Python programs
   python3 --version  # Should be 3.6+
   
   # For SQL programs
   sudo apt-get install sqlite3
   ```

3. **CS50 Library Installation**
   ```bash
   # Install CS50 C library
   wget https://github.com/cs50/libcs50/releases/download/v10.1.1/cs50-10.1.1.tar.gz
   tar -xzf cs50-10.1.1.tar.gz
   cd cs50-10.1.1
   sudo make install
   ```

### Running Programs

#### C Programs
```bash
# Compile
make program_name

# Run
./program_name

# Example for mario
make mario
./mario
```

#### Python Programs
```bash
# Run directly
python program_name.py

# Or with Python 3 explicitly
python3 program_name.py
```

#### Web Applications
```bash
# Flask applications
cd week9-flask/finance
flask run

# Access at http://localhost:5000
```

## Usage Guidelines

### For Students
1. **Try First**: Attempt problems on your own before looking at solutions
2. **Understand**: Don't just copy code - understand the logic and approach
3. **Modify**: Experiment with different approaches and optimizations
4. **Learn**: Use solutions as learning aids, not shortcuts

### For Self-Learners
1. **Follow Along**: Work through problems in order
2. **Practice**: Do additional problems in practice-problems/
3. **Review**: Check your solutions against these implementations
4. **Extend**: Add features or create variations of problems

### For Educators
1. **Reference**: Use as reference material for teaching
2. **Examples**: Show different approaches to problems
3. **Inspiration**: Create new problems based on these examples
4. **Verification**: Check student work against these solutions

## Learning Path

### Beginner Track (Weeks 0-4)
1. **Week 0**: Complete scratch project
2. **Week 1**: Master hello, mario, cash
3. **Week 2**: Focus on caesar and readability
4. **Week 3**: Understand plurality and runoff
5. **Week 4**: Complete filter (more complex)

### Intermediate Track (Weeks 5-7)
1. **Week 5**: Implement speller with hash table
2. **Week 6**: Complete dna and sentiment
3. **Week 7**: Master SQL queries in movies

### Advanced Track (Weeks 8-10)
1. **Week 8**: Build complete homepage
2. **Week 9**: Implement finance with Flask
3. **Week 10**: Complete ethics essay
4. **Final Project**: Capstone project

### Recommended Study Schedule
- **Day 1**: Watch lecture and understand concepts
- **Day 2**: Start problem set, read specifications
- **Day 3**: Implement basic solution
- **Day 4**: Test and debug
- **Day 5**: Optimize and submit
- **Day 6**: Review solutions, understand alternatives
- **Day 7**: Practice with additional problems

## Contributing

### How to Contribute
1. **Fork** the repository
2. **Create** a feature branch
3. **Add** improvements or fixes
4. **Submit** a pull request

### Areas for Contribution
- **Additional solutions**: Alternative implementations
- **Optimizations**: More efficient algorithms
- **Documentation**: Better explanations and comments
- **Tests**: More comprehensive test cases
- **New problems**: Additional practice problems
- **Translations**: Solutions in other languages

### Code Standards
- Follow CS50 style guide for each language
- Add detailed comments explaining logic
- Include test cases where appropriate
- Keep solutions simple and educational
- Add time and space complexity analysis

### Pull Request Process
1. Ensure your code compiles and runs correctly
2. Update documentation if needed
3. Add tests for new features
4. Follow the existing code structure
5. Provide clear description of changes

## Academic Integrity

### Important Notice
⚠️ **This repository is intended for educational purposes only.**

### For CS50 Students
- **DO NOT** copy solutions directly
- **DO** use as a reference after attempting problems
- **DO** understand the concepts behind solutions
- **DO** cite if you use significant portions

### Harvard University Honor Code
By taking CS50, you agree to Harvard's Academic Integrity policy:
- Submit your own work
- Cite any external help
- Don't share your solutions
- Don't search for complete solutions

### Fair Use
These solutions are provided under fair use for:
- Self-learners studying computer science
- Educators preparing course materials
- Students checking their work after submission
- Developers learning new concepts

### Alternative Uses
1. **Learning Resource**: Study different approaches
2. **Debugging Help**: Compare with your implementation
3. **Algorithm Reference**: Understand complex algorithms
4. **Code Review**: Learn from well-structured code
5. **Teaching Aid**: Use in classroom demonstrations

## Additional Resources

### Official CS50 Resources
- [CS50 Website](https://cs50.harvard.edu/2019/)
- [CS50 IDE](https://ide.cs50.io/)
- [CS50 Reference](https://reference.cs50.net/)
- [CS50 Manual Pages](https://manual.cs50.net/)

### Learning Materials
- **Textbooks**: Recommended readings in course syllabus
- **Online Courses**: Supplemental courses on edX
- **Practice Platforms**: LeetCode, HackerRank, Codecademy
- **Community**: CS50 Facebook groups, Discord channels

### Tools and Software
- **Compiler**: GCC for C programs
- **Interpreter**: Python 3.6+ for Python programs
- **Database**: SQLite3 for SQL problems
- **Web Server**: Flask development server
- **Editor**: VS Code, Atom, or CS50 IDE

## Final Project

### Project Ideas
1. **Web Application**: Full-stack web app with database
2. **Mobile App**: iOS or Android application
3. **Game**: Interactive game with graphics
4. **Data Analysis**: Machine learning project
5. **Hardware Project**: IoT or robotics project

### Project Structure
- **Proposal**: Problem statement and approach
- **Implementation**: Complete working code
- **Documentation**: User guide and technical documentation
- **Demo**: Video demonstration
- **Presentation**: Final presentation slides

### Submission Requirements
1. Working implementation
2. Source code with comments
3. README with instructions
4. Video demonstration (≤ 3 minutes)
5. Design documentation

## Support

### Getting Help
- **Course Staff**: Contact via CS50 help channels
- **Community**: Join CS50 communities online
- **Issues**: Open GitHub issues for code problems
- **Discussions**: Use GitHub discussions for questions

### Common Issues
- **Compilation Errors**: Check CS50 library installation
- **Memory Leaks**: Use Valgrind for C programs
- **SQL Errors**: Test queries in SQLite3 directly
- **Web Issues**: Check browser console for errors

### Troubleshooting
```bash
# Common troubleshooting commands

# Check CS50 library
ls /usr/local/include | grep cs50

# Check Python installation
python3 --version
pip3 list | grep cs50

# Reset CS50 IDE
help50 make program_name

# Debug memory issues
valgrind ./program_name
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **Harvard University** for creating and offering CS50
- **David J. Malan** and the CS50 teaching staff
- **CS50 community** for support and collaboration
- **All contributors** who have improved these solutions

---

**⭐ If you find these solutions helpful for your learning journey, please consider giving the repository a star!**

**Remember**: The real value is in the learning process, not just the final solution. Use these resources responsibly and ethically.
