#include <iostream>
#include <string>
#include <unistd.h>
using namespace std;
int m, t=0, s=0, u=0, c=0, col=5, sent=0;
string un, soc;
int main() {
    string r="\033[31m", g="\033[32m", z="\033[0m", f="\033[35m", cl="\033[2J\033[H", in=">>> ", rc=r+"[!]"+z, gc=g+"[+]"+z, status;
    while (true) {
        int ready=1;
        if (s==0) ready=0;
        if (t==0) ready=0;
        if (u==0) ready=0;
        if (c<=0) ready=0;
        status=rc;
        if (ready==1) status=gc;
        cout << cl <<"/====================================================================================""                                                                                  ||\n||"<<f<<"      █████████  ██████  █████ █████ █████ █████  █████  █████ ████ █████ ████    "<<z<<"||\n||"<<f<<"     ░█░░░░███  ███░░███░░███ ░░███ ░░███ ░░███  ███░░  ░░███ ░███ ░░███ ░███     "<<z<<"||\n||"<<f<<"     ░   ███░  ░███████  ░███  ░███  ░░░█████░  ░░█████  ░███ ░███  ░███ ░███     "<<z<<"||\n||"<<f<<"       ███░   █░███░░░   ░░███ ███    ███░░░███  ░░░░███ ░███ ░███  ░███ ░███     "<<z<<"||\n||"<<f<<"      █████████░░██████   ░░█████    █████ █████ ██████  ░░███████  ░░███████     "<<z<<"||\n||"<<f<<"     ░░░░░░░░░  ░░░░░░     ░░░░░    ░░░░░ ░░░░░ ░░░░░░    ░░░░░███   ░░░░░███     "<<z<<"||\n||"<<f<<"                                                          ███ ░███   ███ ░███     "<<z<<"||\n||"<<f<<"                                                         ░░██████   ░░██████      "<<z<<"||\n||"<<f<<"      █████  ████████    ██████   █████   ██████  ████████░░░░░░     ░░░░░░       "<<z<<"||\n|| "<<f<<"    ███░░  ░░███░░███  ███░░███ ███░░   ███░░███░░███░░███                 "<<z<<"      ||\n|| "<<f<<"   ░░█████  ░███ ░███ ░███ ░███░░█████ ░███████  ░███ ░░░                      "<<z<<"  ||\n||   "<<f<<"  ░░░░███ ░███ ░███ ░███ ░███ ░░░░███░███░░░   ░███                      "<<z<<"      ||\n||  "<<f<<"   ██████  ████ █████░░██████  ██████ ░░██████  █████                       "<<z<<"    ||\n|| "<<f<<"   ░░░░░░  ░░░░ ░░░░░  ░░░░░░  ░░░░░░   ░░░░░░  ░░░░░    "<<z<<"                        ||\n||                                                                                  ||\n\\====================================================================================/\n\n" <<"╭───────=="<<f<<"MENU"<<z<<"==───────╮ ╭──────────────=="<<f<<"MANUAL"<<z<<"==──────────────╮ ╭────────────=="<<f<<"GOODLUCK!"<<z<<"==────────────╮\n" << z<< "│ 1."<<f<<" start " << status<<z<< " 2."<<f<<" type "<<z<<"│ │ at first u need to write parameters, │ │ maded by "<<f<<"zevxsyy"<<z<<" without "<<f<<"ksnxqz"<<z<<" :(  │"<<z<<"\n│ 3."<<f<<" social"<<z<<"    4."<<f<<" user "<<z<<"│ │ for attack. and after attack u need  │ │ while ksnxqz looking for            │"<<z<<"\n"<< "│ 5."<<f<<" count"<<z<<"             │ │ to wait "<<f<<"24 - 72 hours"<<z<<"                │ │ new laptop. maded for ragebiting    │"<< z<<"\n│ 6. "<<f<<"info&settings     "<<z<<"│ ╰──────────────────────────────────────╯ │ childs who not reading "<<f<<"README.txt"<<z<<"   │""\n╰──────────────────────╯                                          ╰─────────────────────────────────────╯"<<"\n" <<in;
        cin >> m;
        if (m==0) break;
        if (m==1) {
            if (ready==0) { cout << rc << endl; sleep(1); }
            else {
                for (sent=0; sent<c; sent++) {
                    cout << cl << gc << " | " << sent << "/" << c
                         << " | " << un << " | " << soc << " | ";
                    if (t==1) cout << "sessions";
                    if (t==2) cout << "reports";
                    cout << endl;
                    sleep(1);
                }
            }
        }
        if (m==2) {
            cout << cl << "1. sessions\n2. reports\n0. back\n" << in;
            cin >> t;
            if (t<1) t=0;
            if (t>2) t=0;
        }
        if (m==3) {
            cout << cl << "1. Telegram\n2. WhatsApp\n3. VK\n4. TikTok\n5. Instagram\n0. back\n" << in;
            cin >> s;
            if (s<1) s=0;
            if (s>5) s=0;
            if (s==1) soc="Telegram";
            if (s==2) soc="WhatsApp";
            if (s==3) soc="VK";
            if (s==4) soc="TikTok";
            if (s==5) soc="Instagram";
        }
        if (m==4) {
            cout << "username: ";
            cin >> un;
            u=1;
            if (un=="") u=0;
        }
        if (m==5) {
            cout << "count: ";
            cin >> c;
        }
        if (m==6) {
            cout << "maded by zevxsyy in 15min\n"<< cl << "1. "<<r<<"red"<<z<<"\n2. "<<g<<"green"<<z<<"\n3. "<< "\033[33m" << "yellow"<<z<<"\n4. "<<"\033[34m"<<"blue"<<z<<"\n5."<<"\033[35m"<<" magenta"<<z<<"\n6."<<"\033[36m"<<" cyan"<<z<<"\n7. white\n0. back\n" << in;
            cin >> col;
            if (col==1) f=r;
            if (col==2) f=g;
            if (col==3) f="\033[33m";
            if (col==4) f="\033[34m";
            if (col==5) f="\033[35m";
            if (col==6) f="\033[36m";
            if (col==7) f="\033[37m";
        }
    }
    return 0;
}
