# food-secure
A Food donation coordination platform linking supermarkets, restaurants, and NGOs to distribute excess food.

## Tech Stack
- **Frontend** - React + Tailwind + DaisyUI
- **Backend** - FastAPI
- **Database** - SQLite (for production)


## Run Backend
```Bash
cd backend
python -m venv .venv
# Windows: .venv\Scripts\activate
source .venv/bin/activate
pip install -r requirements.txt
uvicorn app.main:app --reload
# http://127.0.0.1:8000/docs
```

## Run Frontend
```Bash
cd frontend
npm install
npm start
# http://localhost:3000
```

## Screenshots

> Landing Page
<img width="940" height="460" alt="image" src="https://github.com/user-attachments/assets/b2a7fe23-9b5a-46df-8664-4b1649520f1e" />

 
> Login Page
<img width="940" height="459" alt="image" src="https://github.com/user-attachments/assets/f7679a38-cf16-40fa-a992-76ddba410186" />

>Signup Page 
>Users can register on the platform as a Donor or NGO.
<img width="940" height="461" alt="image" src="https://github.com/user-attachments/assets/5c9b4677-64f5-41ab-86c1-b2b5389184b8" />
 
> NGO Dashboard.
> NGOs can claim the available food listed by the donors.
<img width="940" height="460" alt="image" src="https://github.com/user-attachments/assets/9475ea9b-7d16-49a5-878a-5b17843d18a8" />
 
> Confirmation Modal
 <img width="940" height="461" alt="image" src="https://github.com/user-attachments/assets/004d7c7e-9414-4f28-b03f-18304673ef57" />

> Profile Management.
> Donors manage their profile if there are any changes they want to make.
 <img width="940" height="456" alt="image" src="https://github.com/user-attachments/assets/93d6a36a-7c0f-48f9-87b3-f3de677ad311" />

> Donor Dashboard.
> Donors can also see listings by other donors
 <img width="940" height="461" alt="image" src="https://github.com/user-attachments/assets/e66948fd-516e-44fb-8726-90113c8b6d1e" />

>Create Listings.
>Donors can create listings of food items.
 <img width="940" height="460" alt="image" src="https://github.com/user-attachments/assets/6e60aeac-8eaa-40c5-b08f-ba7f14990138" />

> My Listings.
> Donors can view and manage their own listings.
 <img width="940" height="459" alt="image" src="https://github.com/user-attachments/assets/b0b307a8-2a3d-4666-812b-b0bad1cc1b0b" />

> Profile Management.
> Donors can also manage their own profile
 <img width="940" height="460" alt="image" src="https://github.com/user-attachments/assets/a3512b19-f8f1-4184-9b44-043c534d8ca4" />




