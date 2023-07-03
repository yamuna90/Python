# Python - LOOP Excercise

1.  A company decided to give bonus of 5% to employee if his/her year of service is more than 5 years.
Ask user for their salary and year of service and print the net bonus amount.
        year=int(input('how many years of experience?'))
        if year >=5:
            print("you are eligible for the bonus")
        else :
            print('you are not eligilbe for the bonus')

2.Take values of length and breadth of a rectangle from user and check if it is square or not.
    Hint- for Square all sides are equal so breadth=length
            length=int(input('enter the breadth'))
            height=int(input('enter the height'))
            if height==length:
                print('this is square')
            else:
                print('this is rectangle')
