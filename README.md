# C-kodu
Hesap makinesi 
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp7
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("yapmak istediğin işlemin adını gir");
            string name = Console.ReadLine();
            Console.WriteLine("birinci sayı gir");
            int number = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("ikinci sayıyı gir");
            
            int number2 = Convert.ToInt32(Console.ReadLine());

            if (name == "çarpma")
            {
                int çarpım = number * number2;
                Console.WriteLine(çarpım);
            }
            if (name == "toplam")
            {
                int toplam = number + number2;
                Console.WriteLine(toplam);
            }
            if (name == "çıkarma")
            {
                int çıkarma = number - number2;
                Console.WriteLine(çıkarma);
            }
            if (name == "bölme")
            {
                int bölme = number / number2;
                Console.WriteLine(bölme);
            }
            Console.ReadKey();

        }
    }
}
