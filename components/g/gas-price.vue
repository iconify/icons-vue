<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jfcrh0b5r"/><path class="fhnkjvb7c"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gas-price" /></template>
<style>
.fhnkjvb7c {
  d: path("M5.75 6h3v3.5h-3Zm5.75 6.5H14q.103 0 .205-.014m.715-.301q.135-.105.243-.238q.109-.133.184-.287q.076-.154.114-.321T15.5 11V6.5l-1.75-1.75M14 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.jfcrh0b5r {
  d: path("M3 21V5q0-.098.01-.196q.009-.098.028-.194q.02-.097.048-.191q.029-.094.066-.184q.038-.091.084-.178q.046-.086.101-.168t.117-.158t.132-.145t.145-.132t.158-.117t.168-.101q.087-.046.178-.084q.09-.037.184-.066q.094-.028.191-.048q.096-.019.194-.028T5 3h4.5q.098 0 .196.01q.098.009.194.028q.097.02.191.048q.094.029.184.066q.091.038.178.084q.086.046.168.101t.158.117t.145.132t.132.145t.117.158t.101.168q.046.087.084.178q.037.09.066.184q.028.094.048.191q.019.096.028.194T11.5 5v11.243m0 3.5V21m-9 0H12");
}

.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
