while True:
    user_input = input("Введите текст: ")
    if user_input == "ПОКА":
        print("До свидания!")
        break
    elif user_input.isupper():
        print("НЕТ НИ РАЗУ С 1938!")
    else:
        print("АСЬ? ГОВОРИ ГРОМЧЕ ВНУЧОК.")
