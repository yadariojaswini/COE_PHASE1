# COE_PHASE1
##  Scholarship Eligibility Evaluator ##

student_name=input()
percentage_10=int(input())
percentage_12=int(input())
percentage_ug=int(input())
family_income=int(input())
if(percentage_10>85 and percentage_12>85 and percentage_ug>85 and family_income<300000):
    print("FULL Scholarship is eligible by ",student_name)
elif( percentage_ug>70 and family_income<500000):
    print("Partial Scholarship is eligible by",student_name)
else:
    print("not eligible for scholarship")



###   Ration Card Eligibility Checker   ###

family_members=int(input())
annual_income=int(input())
location=input("enter the location 1.rural 2.urban")
if(1 and annual_income<250000 and family_members>3):
    print("the family is eligible for Ration Card ")
elif(2 and annual_income<200000 and family_members>4):
    print("the family is eligible for Ration Card ")
else:
    print("not eligible")


#### generating electrial bill  ####

prev=int(input("enter previous value"))
pres=int(input("enter present value"))
units=prev-pres
total=0
if units<=50:
    total=50*0.50
elif units<=150:
    total=50*0.50+(unit-50)*0.75
elif units<=250:
    total=50*0.50+(100*0.75)+(unit-150)*1.25
else:
    total=50*0.50+(100*0.75)+(100*1.25)+(unit-250)*2.50

bill=total+(total*18)/100
print(bill)


#####  exam scores  ####

internals=int(input())
externals=int(input())
project=int(input())
if(internals>=50 and externals>=50 and project>=50):
    total_score=(((project*70)/100)+((externals*20)/100)+((internals*10)/100))
    print(total_score)
    if(total_score>=90):
        print("grade A")
    elif(total_score>=70):
        print("grade B")
    else:
        print("grade C") 
    print("pass")
else:
    print("fail")


#### festival offers in restaurant ####


 meal_type=int(input("enter your meal type 1.veg 2.non-veg 3.combo"))
quantity=int(input("enter the quantity"))
festival=input("enter festival 1.yes 2.no")
veg=150
non_veg=200
combo=300
if(festival=='YES'):
    if(meal_type=='1'):
        total=veg*quantity
        bill=total-(total*10)/100
    elif(meal_type=='2'):
        total=non_veg*quantity
        bill=total-(total*10)/100  
    else:
        total=combo*quantity
        bill=total-(total*10)/100     
else:
    if(meal_type=='1'):
        bill=veg*quantity
    elif(meal_type=='2'):
        bill=non_veg*quantity 
    else:
        bill=combo*quantity    
    
print(bill)
if(bill>=1000):
    print("add free desert")
bill=bill+(bill*5)/100
print(bill)












    
