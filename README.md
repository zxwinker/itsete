# itsete
class Car:
    def __init__(self, make, model, year):
        self.make, self.model, self.year = make, model, year

    def get_info(self):
        return "2020 toyota Corola"


class Employee:
    def __init__(self, name, position, salary):
        self.name, self.salary = name, salary

    def get_salary_info(self):
        return "Заробітна плата Іван : 50000"



print(Car("Toyota", "Corola", 2020).get_info())
print(Employee("Іван", "Менеджер", 50000).get_salary_info())
