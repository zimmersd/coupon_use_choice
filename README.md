# coupon_use_choice

A project that seeks to answer the question, "Will a customer accept the coffee coupon?"

This is primarily a learning project for introductory data analysis.

It uses some grouping and counting methods to find what properties in the data are associated
with a greater likelihood of accepting coffee coupons.

We looked at coffee coupons in particular because they were the largest share of coupons (~30%) 
but had one of the lower acceptance rates (~50%).

After splitting the data into various groups based on age, income, time of day, etc., we counted
the number of times certain values occured for groups with greater than a 50% acceptance rate and ranked
the values.

Some of the standout properties include:

- **longer coupon expiration windows**
- **closer proximity to the coupon location upon delivery**
- **having no urgent destination**
- **good/warmer weather**
- **time of 10 am or 2 pm**
- **being with friends or partners**
- **mid to high coffee place frequency**
- **single**
- __income lower than $50k__

Link to Jupyter notebook: <https://github.com/zimmersd/coupon_use_choice/blob/main/coffee_coupon_acceptance.ipynb>
