# Calcule-Gasoline
# This code is very simple, im studying program about 1 month or less, so I made this!
km = float(input('\033[33mHow many kilometers will be driven?'))
lc = float(input('\033[34mHow much does the car go per liter of gas?'))
p = float(input('\033[35mHow many people go in the car?'))
g = float(input('\033[36mWhat is the price of gasoline currently?'))
vg = (km * g) / lc
if p > 1:
    print('\033(32mThe total cost of the travel will be {:.2f}$ to each people!'.format(vg / p))
else:
    print(f'\033[The travel cost will be {vg:.2f}$!')
