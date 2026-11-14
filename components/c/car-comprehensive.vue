<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hdpi5xb_y"/><path class="zh67nkbqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:car-comprehensive" /></template>
<style>
.hdpi5xb_y {
  d: path("M4.5 11.75h-1a1 1 0 0 1-1-1V9A1.5 1.5 0 0 1 4 7.5h2L8.5 4h5l3 3.5H18A1.5 1.5 0 0 1 19.5 9v1.75a1 1 0 0 1-1 1H17m-8.5 0H13");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zh67nkbqn {
  d: path("M4.5 11.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm11.961 1.366q.129-.138.229-.297q.101-.159.17-.335q.07-.175.105-.36T17 11.75q0-.098-.01-.196q-.009-.098-.028-.194q-.02-.097-.048-.191q-.029-.094-.066-.184q-.038-.091-.084-.178q-.046-.086-.101-.168t-.117-.158t-.132-.145t-.145-.132t-.158-.117t-.168-.101q-.087-.046-.178-.084q-.09-.037-.184-.066q-.094-.028-.191-.048q-.096-.019-.194-.028T15 9.75t-.196.01q-.098.009-.194.028q-.097.02-.191.048q-.094.029-.184.066q-.091.038-.178.084q-.086.046-.168.101t-.158.117t-.145.132t-.132.145t-.117.158t-.101.168q-.046.087-.084.178q-.037.09-.066.184q-.028.094-.048.191q-.019.096-.028.194t-.01.196q0 .094.009.188t.026.186q.018.093.044.183q.026.091.061.178q.035.088.077.172q.043.084.093.163q.051.08.108.154q.058.075.123.143q.064.069.135.132q.07.062.146.117t.157.104t.166.088t.174.073q.089.032.18.055q.091.024.184.039t.187.021m3.63 1.504l3 1.25v2c0 1.75-1.25 2.75-3 3.5c-1.75-.75-3-1.75-3-3.5v-2Z");
}

</style>
