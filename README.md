class Student
{ 
    String name;
    String rollno;
    double marks1;
    double marks2;
    
    public student()
    {
        marks1=0;
        marks2=0;
    }
public student(String n, String r, double m1, double m2)
  {
    name = n;
    rollno = r;
    marks1 = m1;
    marks2 = m2;
  }
 public String.getName()
       {return(name);}
 public String.getRollno()
       {return(rollno);}
 public String.getMarks1()
       {return(marks1);}
 public String.getMarks2()
       {return(marks2);}
}

//new

class Testclass
{
    public static void main(String args[])
    {
        student S1 = new.student("Abc","Bt123",50,80);
        student S2 = new.student("efg","BT245",60,80);
        double m1 = (S1.getMarks1() + S1.getMarks2())/2;
        double m2 = (S2.getMarks1() + S2.getMarks2())/2;
        
    if (m1>m2)
      {System.out.println("Higher marks by " + S1.getName());}
    else if (m2>m1)
      {System.out.println("Higher marks by " + S2.getName());}
    else
      {System.out.println("Equal score");}
    
}

