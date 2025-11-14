# The Fighting Maiden 🎮⚔️

A 2D action-adventure game built in C++ for Raspberry Pi, featuring real-time combat, NPC interactions, and hazard-dodging gameplay.

## 🎯 Overview

Navigate through a dangerous world, dodge hazards, defeat enemies, and reach the ultimate goal: the blue warp! Receive assistance from NPCs along your journey in this fast-paced embedded systems game.

## 👥 Development Team

- Xavier Hill Roy
- Bryce Chevallier
- Matthew Korkola
- Samuel Near
- Yakup Tezcan

## 🎮 Gameplay

### Objective
Survive hazards, battle enemies, and reach the blue warp portal to win!

### Controls

| Key | Action |
|-----|--------|
| `W` | Move Up |
| `S` | Move Down |
| `A` | Move Left |
| `D` | Move Right |
| `K` | Attack |
| `M` (hold) | Run |
| `P` | Pause Game |
| `U` | Unpause Game |
| `Y` | Quit Game |

> **⚠️ Combat Note:** There is a brief cooldown period after each attack. Time your attacks strategically!

## 🚀 Getting Started

### Prerequisites
- Raspberry Pi (tested on Raspberry Pi 3/4)
- C++ compiler (g++)
- Standard C++ libraries

### Building and Running

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd fighting-maiden
   ```

2. **Compile and run**
   ```bash
   g++ main.cpp -o fighting_maiden
   ./fighting_maiden
   ```

> **Important:** Ensure all test cases in `main.cpp` are commented out before running the game (they are commented by default on submission).

### Running Test Cases

To run individual test cases:

1. Comment out the main game function in `main.cpp`
2. Uncomment the desired test case
3. Compile and run as above

> **Note:** Only one main function should be active at a time. Comment out all other main functions from both `main.cpp` and other test files.

## Technical Details

### Architecture
- **Language:** C++
- **Platform:** Raspberry Pi (embedded systems)
- **Design Pattern:** Object-oriented with UML documentation
- **Testing:** Test-Driven Development (TDD) approach
- **Documentation:** Comprehensive inline documentation and UML diagrams

### Key Features
- Real-time combat system with attack cooldowns
- NPC interaction system
- Collision detection and hazard avoidance
- Movement with run/walk mechanics
- Pause/unpause functionality

## Testing

The project includes comprehensive test cases covering:
- Player movement mechanics
- Combat system functionality
- Collision detection
- NPC interactions
- Game state management



## Educational Context

This project was developed as part of a software engineering course, demonstrating:
- Team collaboration and project management
- Requirements analysis and UML design
- Test-Driven Development methodology
- Embedded systems programming
- C++ systems programming on resource-constrained hardware

## 📝 Development Process

- **Requirements Gathering:** Translated user stories into functional requirements
- **Design:** Created UML diagrams for system architecture
- **Implementation:** Iterative development with TDD approach
- **Testing:** Comprehensive unit and integration tests
- **Documentation:** Inline code documentation and technical diagrams

##  Known Issues

- Test cases must be manually commented/uncommented
- Single main function limitation (C++ compilation requirement)

## Acknowledgments

Developed as part of CS3307 at Western University 

---

**Enjoy the adventure! May your blade strike true! ⚔️**
