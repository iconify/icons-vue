<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mba7c104x"/><path class="y-nelcc9l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:car-finance" /></template>
<style>
.mba7c104x {
  d: path("M4.5 11h-1q-1 0-1-1V7.5l3-1.25L8 3h7l2.75 3.25l1.75.5q1 .25 1 1.25v2q0 1-1 1h-3m-8 0h4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y-nelcc9l {
  d: path("M4.5 11a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm11.007 1.728q.113-.066.216-.146t.195-.172t.172-.196q.079-.104.144-.217q.065-.114.115-.234t.083-.247q.034-.126.051-.256q.017-.129.017-.26q0-.098-.01-.196q-.009-.098-.028-.194q-.02-.097-.048-.191q-.029-.094-.066-.184q-.038-.091-.084-.178q-.046-.086-.101-.168t-.117-.158t-.132-.145t-.145-.132t-.158-.117t-.168-.101q-.087-.046-.178-.084q-.09-.037-.184-.066q-.094-.028-.191-.048q-.096-.019-.194-.028T14.5 9t-.196.01q-.098.009-.194.028q-.097.02-.191.048q-.094.029-.184.066q-.091.038-.178.084q-.086.046-.168.101t-.158.117t-.145.132t-.132.145t-.117.158t-.101.168q-.046.087-.084.178q-.037.09-.066.184q-.028.094-.048.191q-.019.096-.028.194T12.5 11q0 .126.016.252q.016.125.047.248q.032.122.079.24t.108.228q.061.111.136.213q.074.102.161.194t.185.172t.205.147m1.313 8.556l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

</style>
