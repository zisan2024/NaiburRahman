// Base class
class Animal {
    // Field of the base class
    String name;

    // Constructor of the base class
    Animal(String name) {
        this.name = name; // Using 'this' to refer to the current instance's field
    }

    // Method of the base class
    void makeSound() {
        System.out.println("Some generic animal sound.");
    }

    // Method to display information about the animal
    void displayInfo() {
        System.out.println("Animal Name: " + this.name); // Using 'this' to refer to the current instance's field
    }
}

// Derived class
class Dog extends Animal {
    // Additional field of the derived class
    String breed;

    // Constructor of the derived class
    Dog(String name, String breed) {
        super(name); // Using 'super' to call the constructor of the base class
        this.breed = breed; // Using 'this' to refer to the current instance's field
    }

    // Overriding the method of the base class
    @Override
    void makeSound() {
        System.out.println("Woof Woof!");
    }

    // Method to display information about the dog
    void displayInfo() {
        super.displayInfo(); // Using 'super' to call the method of the base class
        System.out.println("Dog Breed: " + this.breed); // Using 'this' to refer to the current instance's field
    }
}

public class Main {
    public static void main(String[] args) {
        // Creating an instance of the Dog class
        Dog myDog = new Dog("Buddy", "Golden Retriever");

        // Calling methods of the Dog class
        myDog.makeSound(); // Calls the overridden method in Dog
        myDog.displayInfo(); // Calls the method in Dog, which also calls the base class's method
    }
}
