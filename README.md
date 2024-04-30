const dom = 1
const seg = 2
const ter = 3
const qua = 4
const qui = 5
const sex = 6
const sab = 7

let atividade = prompt("atividade semanal")

if (atividade == dom) {
   document.write("você vai jogar bola")

} else if (atividade == seg) {
   document.write("você vai estudar")

}else if (atividade == ter) {
   document.write("você vai assistir um filme")

}else if (atividade == qua) {
   document.write("você vai sair com a namorada ")  

}else if (atividade == qui) {
   document.write("você vai fazer compras ")

} else if (atividade == sex) {
   document.write("você vai sair com amigos")

}else if (atividade == sab) {
    document.write("você vai descançar")

} else {
    alert("resposta não indentificada")
    
}
