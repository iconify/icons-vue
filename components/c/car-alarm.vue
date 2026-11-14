<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k0dkeobxo"/><path class="stifdhbdx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:car-alarm" /></template>
<style>
.k0dkeobxo {
  d: path("M4.5 12H3a1 1 0 0 1-1-1V8.5A1.5 1.5 0 0 1 3.5 7h1L7 3.5h6.5L16 7h1a1.5 1.5 0 0 1 1.5 1.5V11a1 1 0 0 1-1 1h-1m-8 0h4");
}

.stifdhbdx {
  d: path("M4.5 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm11.88.684q.12-.332.12-.684q0-.098-.01-.196q-.009-.098-.028-.194q-.02-.097-.048-.191q-.029-.094-.066-.184q-.038-.091-.084-.178q-.046-.086-.101-.168t-.117-.158t-.132-.145t-.145-.132t-.158-.117t-.168-.101q-.087-.046-.178-.084q-.09-.037-.184-.066q-.094-.028-.191-.048q-.096-.019-.194-.028T14.5 10t-.196.01q-.098.009-.194.028q-.097.02-.191.048q-.094.029-.184.066q-.091.038-.178.084q-.086.046-.168.101t-.158.117t-.145.132t-.132.145t-.117.158t-.101.168q-.046.087-.084.178q-.037.09-.066.184q-.028.094-.048.191q-.019.096-.028.194T12.5 12t.01.196q.009.098.028.194q.02.097.048.191q.029.094.066.184q.038.091.084.178q.046.086.101.168t.117.158t.132.145t.145.132t.158.117t.168.101q.087.046.178.084q.09.037.184.066q.094.028.191.048q.096.019.194.028t.196.01q.14 0 .278-.019m.972 5.269h5.5L20.5 18v-1a2 2 0 0 0-4 0v1Zm2 2.25h1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
