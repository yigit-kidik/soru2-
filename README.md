import random
liste = []
for i in range(1,21):
    liste.append(random.randint(1,100))
print(liste)
kume = set(liste)
liste = list(kume)
print(liste)
