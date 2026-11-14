<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xu0ih13jv"/><path class="dpbbrrlzl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:car-check" /></template>
<style>
.dpbbrrlzl {
  d: path("M4.5 13a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10.791 1.527q.167-.141.299-.314t.224-.371t.139-.411T16 13q0-.098-.01-.196q-.009-.098-.028-.194q-.02-.097-.048-.191q-.029-.094-.066-.184q-.038-.091-.084-.178q-.046-.086-.101-.168t-.117-.158t-.132-.145t-.145-.132t-.158-.117t-.168-.101q-.087-.046-.178-.084q-.09-.037-.184-.066q-.094-.028-.191-.048q-.096-.019-.194-.028T14 11t-.196.01q-.098.009-.194.028q-.097.02-.191.048q-.094.029-.184.066q-.091.038-.178.084q-.086.046-.168.101t-.158.117t-.145.132t-.132.145t-.117.158t-.101.168q-.046.087-.084.178q-.037.09-.066.184q-.028.094-.048.191q-.019.096-.028.194T12 13q0 .091.008.181q.009.091.025.18q.016.09.041.178q.024.087.057.172q.032.085.072.167q.04.081.087.159t.101.151t.115.141t.126.13q.067.063.138.118q.072.056.149.106q.076.049.157.091q.08.042.165.076q.084.035.171.062t.176.045t.179.029M14.75 18l2 2L21 15.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xu0ih13jv {
  d: path("M4.5 13H3v-3q0-1 1-1.25l2.5-.5L8.75 4.5H14l3 3.75l2.5.5q1 .25 1 1.25v2.274m-.674.726H16m-7.5 0H12");
}

</style>
