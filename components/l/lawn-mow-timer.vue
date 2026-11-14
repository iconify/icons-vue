<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h1woowb9a"/><path class="xetqorbiw"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lawn-mow-timer" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.h1woowb9a {
  d: path("M13.497 14H2.5v-2.5q0-.098.01-.196q.009-.098.028-.194q.02-.097.048-.191q.029-.094.066-.184q.038-.091.084-.178q.046-.086.101-.168t.117-.158t.132-.145t.145-.132t.158-.117t.168-.101q.087-.046.178-.084q.09-.037.184-.066q.094-.028.191-.048q.096-.019.194-.028T4.5 9.5H12q.353-.006.704.033q.351.04.694.124q.344.084.673.211t.64.295q.311.169.598.375q.286.207.544.448t.482.515q.225.272.413.571");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xetqorbiw {
  d: path("m6 9.5l-2-7H2.5m1 13.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m9.618-1.658q-.248-.167-.533-.255Q12.299 14 12 14q-.098 0-.196.01q-.098.009-.194.028q-.097.02-.191.048q-.094.029-.184.066q-.091.038-.178.084q-.086.046-.168.101t-.158.117t-.145.132t-.132.145t-.117.158t-.101.168q-.046.087-.084.178q-.037.09-.066.184q-.028.094-.048.191q-.019.096-.028.194T10 16t.009.194q.01.097.029.193q.019.095.047.188q.028.094.065.184q.036.09.082.176q.045.086.099.167t.115.157t.13.145q.068.069.143.132q.075.062.155.117q.081.055.166.102t.175.084q.089.039.182.068t.188.05q.096.02.192.031q.097.01.194.012m2.779 0a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

</style>
