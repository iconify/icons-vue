<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l_vf58bry"/><path class="t_w12qbng"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:airport-transfer" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l_vf58bry {
  d: path("M5 11H2.5V8A1.5 1.5 0 0 1 4 6.5h1.5l2-3H15l3 3h2A1.5 1.5 0 0 1 21.5 8v3H19m-4 0H9");
}

.t_w12qbng {
  d: path("M5 11a2 2 0 1 0 4 0a2 2 0 1 0-4 0m13.378 1.449q.148-.14.264-.307t.196-.354t.121-.386T19 11q0-.098-.01-.196q-.009-.098-.028-.194q-.02-.097-.048-.191q-.029-.094-.066-.184q-.038-.091-.084-.178q-.046-.086-.101-.168t-.117-.158t-.132-.145t-.145-.132t-.158-.117t-.168-.101q-.087-.046-.178-.084q-.09-.037-.184-.066q-.094-.028-.191-.048q-.096-.019-.194-.028T17 9t-.196.01q-.098.009-.194.028q-.097.02-.191.048q-.094.029-.184.066q-.091.038-.178.084q-.086.046-.168.101t-.158.117t-.145.132q-.07.069-.132.145t-.117.158t-.101.168t-.084.178q-.037.09-.066.184q-.028.094-.048.191q-.019.096-.028.194T15 11q0 .162.026.322t.078.313t.127.297t.173.273t.214.241t.251.204q.134.091.28.16t.303.113M18 15.25v6.25M14.5 19l3.5-1.75L21.5 19m-5.25 2.5h3.5");
}

</style>
