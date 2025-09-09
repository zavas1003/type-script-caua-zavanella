# type-script-caua-zavanella

exercio 1 function saudacao(): void {
  console.log("Olá, Mundo!");
}

// Chamando a função
saudacao();


EXERCICIO 2 
function dizerOla(nome: string): void {
  console.log(`Olá, ${nome}!`);
}

dizerOla("Eduardo");
dizerOla("Pietro");


EXERCICIO 3 
function somar(a: number, b: number): number {
  return a + b;
}

console.log(`Resultado: ${somar(10, 5)}`);





EXERCICIO 4 
function subtrair(a: number, b: number): number {
  return a - b;
}

console.log(`Resultado: ${subtrair(20, 8)}`);

EXERCICIO 5  function multiplicar(a: number, b: number): number {
  return a * b;
}

console.log(`Resultado: ${multiplicar(6, 7)}`);


EXERCICIO 5 function multiplicar(a: number, b: number): number {
  return a * b;
}

console.log(`Resultado: ${multiplicar(6, 7)}`);



EXERCICIO 6 function dividir(a: number, b: number): number {
  if (b === 0) {
    console.log("Erro: divisão por zero");
    return NaN;
  }
  return a / b;
}
console.log(`Resultado: ${dividir(20, 4)}`);

EXERCICIO 7 
function dobro(n: number): number {
  return n * 2;
}

console.log(`Dobro de 12 = ${dobro(12)}`);


EXERCICIO 8 function parOuImpar(n: number): string {
  if (n % 2 === 0) {
    return "Par";
  } else {
    return "Ímpar";
  }
}


EXERCICIO 9 function media(n1: number, n2: number, n3: number): number {
  return (n1 + n2 + n3) / 3;
}

console.log(`Média = ${media(7, 8, 6).toFixed(2)}`);



EXERCICIO 10 function verificarAprovacao(nota: number, faltas: number): string {
  if (nota >= 7 && faltas <= 10) {
    return "Aprovado";
  } else {
    return "Reprovado";
  }
}

console.log(verificarAprovacao(8, 5));
console.log(verificarAprovacao(6, 12));


