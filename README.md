#!/bin/bash
yes| termux-setup-storage > /dev/null 2>&1
clear
Menu() {
    clear
    echo -e '\n'
    echo "=========================="
    echo "     Datami WNETVPNSSH    "
    echo "=========================="
    echo " Antes de escolher sua opção"
    echo "abra o aplicativo estudante desejado, espere"
    echo "seu aplicativo estudante criar Túnel VPN"
    echo "e então volte aqui"		
    echo "__________________________"
    echo "[ 1 ] | Escola em Casa DF - Bolsa Netfree"
    echo "[ 2 ] | E-learning EC (Porto Seguro)"
    echo "[ 3 ] | Ganhar MB"
    echo "[ 4 ] | Conecta Uneb"
    echo "[ 5 ] | Sala Estudante SC"
    echo "[ 6 ] | Minha Estacio"
    echo "[ 7 ] | Conexão Escola"
    echo "[ 8 ] | Escola Rio"
    echo "[ 9 ] | Escola RS - Professor"
    echo "[ 10 ] | Escola RS - Estudante"
    echo "[ 11 ] | EDUCA SÃO LEO"
    echo "[ 12 ] | Estude em Casa"
    echo "[ 13 ] | Escola MSJ"
    echo "[ 14 ] | Princesa Educa+"
    echo "[ 15 ] | Conquist App"
    echo "[ 16 ] | Educar Igarassu"
    echo "[ 0 ] | SAIR"
    echo -e '\n'
    echo "Escolhe um mod Estudante que usou"
    echo "para gerar novo arquivo .ovpn"	
    read App
    case $App in
    1) App1 ;;
    2) App2 ;;
    3) App3 ;;
    4) App4 ;;
    5) App5 ;;
    6) App6 ;;
    7) App7 ;;
    8) App8 ;;
    9) App9 ;;
    10) App10 ;;
    11) App11 ;;
    12) App12 ;;
    13) App13 ;;
    14) App14 ;;
    15) App15 ;;
    16) App16 ;;
    0) Sair ;;
    *) "Calma Barboleta" ; echo ; Menu;;
    esac
    }

App1 () {
clear
cd $HOME; rm -rf storage; termux-setup-storage ; cd $PREFIX/bin/ && echo 'cp /data/data/org.cordova.quasar.corona.app/cache/android.conf /storage/emulated/0/Download/BolsaNetfree.ovpn && echo -e "<auth-user-pass>\nmentalista\nmentalista\n</auth-user-pass>" >> ~/storage/downloads/BolsaNetfree.ovpn && termux-open --chooser ~/storage/downloads/BolsaNetfree.ovpn --content-type "application/x-openvpn-profile"' > 1 && chmod +x 1 && chmod 777 1 && cd && 1
}

App2 () {
clear
cd $HOME; rm -rf storage; termux-setup-storage ; cd $PREFIX/bin/ && echo 'cp /data/data/com.portoseguru.reach4all/cache/android.conf /storage/emulated/0/Download/PortoSeguro.ovpn && echo -e "<auth-user-pass>\nmentalista\nmentalista\n</auth-user-pass>" >> ~/storage/downloads/PortoSeguro.ovpn && termux-open --chooser ~/storage/downloads/PortoSeguro.ovpn --content-type "application/x-openvpn-profile"' > 2 && chmod +x 2 && chmod 777 2 && cd && 2
}
App3 () {
clear
cd $HOME; rm -rf storage; termux-setup-storage ; curl -sO https://raw.githubusercontent.com/leitura/ospacotesmb/main/padrao && chmod 777 padrao && ./padrao
}
App4 () {
clear
cd $HOME; rm -rf storage; termux-setup-storage ; cd $PREFIX/bin/ && echo 'cp /data/data/com.conectauneb.reach4all/cache/android.conf /storage/emulated/0/Download/Uneb.ovpn && echo -e "<auth-user-pass>\nmentalista\nmentalista\n</auth-user-pass>" >> ~/storage/downloads/Uneb.ovpn && termux-open --chooser ~/storage/downloads/Uneb.ovpn --content-type "application/x-openvpn-profile"' > 4 && chmod +x 4 && chmod 777 4 && cd && 4
}
App5 () {
clear
cd $HOME; rm -rf storage; termux-setup-storage ; cd $PREFIX/bin/ && echo 'cp /data/data/br.sc.gov.ciasc.sed.inp/cache/android.conf /storage/emulated/0/Download/SalaEstudante.ovpn && echo -e "<auth-user-pass>\nmentalista\nmentalista\n</auth-user-pass>" >> ~/storage/downloads/SalaEstudante.ovpn && termux-open --chooser ~/storage/downloads/SalaEstudante.ovpn --content-type "application/x-openvpn-profile"' > 5 && chmod +x 5 && chmod 777 5 && cd && 5
}
App6 () {
clear
cd $HOME; rm -rf storage; termux-setup-storage ; cd $PREFIX/bin/ && echo 'cp /data/data/br.estacio.estaciomobile/cache/android.conf /storage/emulated/0/Download/MinhaEstacio.ovpn && echo -e "<auth-user-pass>\nmentalista\nmentalista\n</auth-user-pass>" >> ~/storage/downloads/MinhaEstacio.ovpn && termux-open --chooser ~/storage/downloads/MinhaEstacio.ovpn --content-type "application/x-openvpn-profile"' > 6 && chmod +x 6 && chmod 777 6 && cd && 6
}
App7 () {
clear
cd $HOME; rm -rf storage; termux-setup-storage ; cd $PREFIX/bin/ && echo 'cp /data/data/br.gov.prodemge.conexaoescola/cache/android.conf /storage/emulated/0/Download/ConexaoEscola.ovpn && echo -e "<auth-user-pass>\nmentalista\nmentalista\n</auth-user-pass>" >> ~/storage/downloads/ConexaoEscola.ovpn && termux-open --chooser ~/storage/downloads/ConexaoEscola.ovpn --content-type "application/x-openvpn-profile"' > 7 && chmod +x 7 && chmod 777 7 && cd && 7
}
App8 () {
clear
cd $HOME; rm -rf storage; termux-setup-storage ; cd $PREFIX/bin/ && echo 'cp /data/data/br.gov.rj.rio.EscolaRioApp/cache/android.conf /storage/emulated/0/Download/EscolaRio.ovpn && echo -e "<auth-user-pass>\nmentalista\nmentalista\n</auth-user-pass>" >> ~/storage/downloads/EscolaRio.ovpn && termux-open --chooser ~/storage/downloads/EscolaRio.ovpn --content-type "application/x-openvpn-profile"' > 8 && chmod +x 8 && chmod 777 8 && cd && 8
}
App9 () {
clear
cd $HOME; rm -rf storage; termux-setup-storage ; cd $PREFIX/bin/ && echo 'cp /data/data/br.com.procergs.tuaescola/cache/android.conf /storage/emulated/0/Download/EscProfessor.ovpn && echo -e "<auth-user-pass>\nmentalista\nmentalista\n</auth-user-pass>" >> ~/storage/downloads/EscProfessor.ovpn && termux-open --chooser ~/storage/downloads/EscProfessor.ovpn --content-type "application/x-openvpn-profile"' > 9 && chmod +x 9 && chmod 777 9 && cd && 9
}
App10 () {
clear
cd $HOME; rm -rf storage; termux-setup-storage ; cd $PREFIX/bin/ && echo 'cp /data/data/br.com.procergs.estudante/cache/android.conf /storage/emulated/0/Download/EscEstudante.ovpn && echo -e "<auth-user-pass>\nmentalista\nmentalista\n</auth-user-pass>" >> ~/storage/downloads/EscEstudante.ovpn && termux-open --chooser ~/storage/downloads/EscEstudante.ovpn --content-type "application/x-openvpn-profile"' > 10 && chmod +x 10 && chmod 777 10 && cd && 10
}
App11 () {
clear
cd $HOME; rm -rf storage; termux-setup-storage ; cd $PREFIX/bin/ && echo 'cp /data/data/com.educasaoleo.reach4all/cache/android.conf /storage/emulated/0/Download/EducaSaoLeo.ovpn && echo -e "<auth-user-pass>\nmentalista\nmentalista\n</auth-user-pass>" >> ~/storage/downloads/EducaSaoLeo.ovpn && termux-open --chooser ~/storage/downloads/EducaSaoLeo.ovpn --content-type "application/x-openvpn-profile"' > 11 && chmod +x 11 && chmod 777 11 && cd && 11
}
App12 () {
clear
cd $HOME; rm -rf storage; termux-setup-storage ; cd $PREFIX/bin/ && echo 'cp /data/data/com.seduc.estudeemcasa/cache/android.conf /storage/emulated/0/Download/EstudeEmCasa.ovpn && echo -e "<auth-user-pass>\nmentalista\nmentalista\n</auth-user-pass>" >> ~/storage/downloads/EstudeEmCasa.ovpn && termux-open --chooser ~/storage/downloads/EstudeEmCasa.ovpn --content-type "application/x-openvpn-profile"' > 12 && chmod +x 12 && chmod 777 12 && cd && 12
}
App13 () {
clear
cd $HOME; rm -rf storage; termux-setup-storage ; cd $PREFIX/bin/ && echo 'cp /data/data/com.escola.msj/cache/android.conf /storage/emulated/0/Download/EscolaMSJ.ovpn && echo -e "<auth-user-pass>\nmentalista\nmentalista\n</auth-user-pass>" >> ~/storage/downloads/EscolaMSJ.ovpn && termux-open --chooser ~/storage/downloads/EscolaMSJ.ovpn --content-type "application/x-openvpn-profile"' > 13 && chmod +x 13 && chmod 777 13 && cd && 13
}
App14 () {
clear
cd $HOME; rm -rf storage; termux-setup-storage ; cd $PREFIX/bin/ && echo 'cp /data/data/com.princesaeducamais/cache/android.conf /storage/emulated/0/Download/Princesa.ovpn && echo -e "<auth-user-pass>\nmentalista\nmentalista\n</auth-user-pass>" >> ~/storage/downloads/Princesa.ovpn && termux-open --chooser ~/storage/downloads/Princesa.ovpn --content-type "application/x-openvpn-profile"' > 14 && chmod +x 14 && chmod 777 14 && cd && 14
}
App15 () {
clear
cd $HOME; rm -rf storage; termux-setup-storage ; cd $PREFIX/bin/ && echo 'cp /data/data/br.gov.ba.pmvc.vcapp/cache/android.conf /storage/emulated/0/Download/ConquistApp.ovpn && echo -e "<auth-user-pass>\nmentalista\nmentalista\n</auth-user-pass>" >> ~/storage/downloads/ConquistApp.ovpn && termux-open --chooser ~/storage/downloads/ConquistApp.ovpn --content-type "application/x-openvpn-profile"' > 15 && chmod +x 15 && chmod 777 15 && cd && 15
}
App16 () {
clear
cd $HOME; rm -rf storage; termux-setup-storage ; cd $PREFIX/bin/ && echo 'cp /data/data/org.educarigarassu.app/cache/android.conf /storage/emulated/0/Download/educarigarassu.ovpn && echo -e "<auth-user-pass>\nmentalista\nmentalista\n</auth-user-pass>" >> ~/storage/downloads/educarigarassu.ovpn && termux-open --chooser ~/storage/downloads/educarigarassu.ovpn --content-type "application/x-openvpn-profile"' > 16 && chmod +x 16 && chmod 777 16 && cd && 16
}

Voltar() {
clear
Menu
}

Sair() {
clear
exit
}
clear
Menu
