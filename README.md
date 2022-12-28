import java.util.Scanner;
public class GuestRecord {
        public static void InputTamuUndangan() {
            Scanner scn = new Scanner(System.in);
            String[] tamu = new String[10];
            System.out.println("Jumlah Tamu Undangan yang telah diinput : " + tamu.length);
        }
        public static void main(String[] args) {
            EventOrganiser tamu1 = new EventOrganiser("001","Dwi","Tegal","dwi@gmail.com",20883);
            System.out.println("Tamu 1");
            tamu1.CetakNamaTamuUndangan();
            System.out.println();

            EventOrganiser tamu2 = new EventOrganiser("002","Adi","Brebes","adi@gmail.com",98345);
            System.out.println("Tamu 2");
            tamu2.CetakNamaTamuUndangan();
            System.out.println();

            EventOrganiser tamu3 = new EventOrganiser("003","Budi","Cirebon","budi@gmail.com",78569);
            System.out.println("Tamu 3");
            tamu3.CetakNamaTamuUndangan();
            System.out.println();

            EventOrganiser tamu4 = new EventOrganiser("004","Tomi","Tegal","tomi@gmail.com",56788);
            System.out.println("Tamu 4");
            tamu4.CetakNamaTamuUndangan();
            System.out.println();

            EventOrganiser tamu5 = new EventOrganiser("005","Ayu","Cirebon","ayu@gmail.com",98643);
            System.out.println("Tamu 5");
            tamu5.CetakNamaTamuUndangan();
            System.out.println();

            EventOrganiser tamu6 = new EventOrganiser("006","Roy","Tegal","roy@gmail.com",59856);
            System.out.println("Tamu 6");
            tamu6.CetakNamaTamuUndangan();
            System.out.println();

            EventOrganiser tamu7 = new EventOrganiser("007","Rio","Jakarta","rio@gmail.com",32345);
            System.out.println("Tamu 7");
            tamu7.CetakNamaTamuUndangan();
            System.out.println();

            EventOrganiser tamu8 = new EventOrganiser("008","Meli","Bandung","meli@gmail.com",66549);
            System.out.println("Tamu 8");
            tamu8.CetakNamaTamuUndangan();
            System.out.println();

            EventOrganiser tamu9 = new EventOrganiser("009","Caca","Jakarta","caca@gmail.com",79875);
            System.out.println("Tamu 9");
            tamu9.CetakNamaTamuUndangan();
            System.out.println();

            EventOrganiser tamu10 = new EventOrganiser("010","Devi","Cianjur","devi@gmail.com",22345);
            System.out.println("Tamu 10");
            tamu10.CetakNamaTamuUndangan();
            System.out.println();

            InputTamuUndangan();
            System.out.println();
            EventOrganiser.PrintGuest();
        }
    }
