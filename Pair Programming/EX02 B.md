Calvin Zhou, Kyle Streit
Normalization Assignment EX02B


1NF, Functional Dependencies:
PetName - PetType, PetBreed, PetDOB
OwnerFirstName, OwnerLastName - OwnerPhone, OwnerEmail
Service - Date, Charge

2NF: 
PET(PetName, PetType, PetBreed, PetDOB, OwnerFirstName, OwnerLastName)
OWNER(OwnerFirstName, OwnerLastName, OwnerPhone, OwnerEmail)
Service(PetName, Service, Date, Charge)

3NF:
PetID(PetName, PetType, PetBreed, PetDOB, OwnerFirstName, OwnerLastName)
OwnerPhone(OwnerFirstName, OwnerLastName, OwnerEmail)
PetId(PetName, Service, Date, Charge)
Assigning each pet a specific and unique pet ID allows each pet to be easily found and identified. This will also allow info to be updated without causing any modification issues. 
