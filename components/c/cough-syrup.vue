<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ca5hvzq_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cough-syrup" /></template>
<style>
.ca5hvzq_p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.5h5A1.5 1.5 0 0 1 13 4a1.5 1.5 0 0 1-1.5 1.5h-5A1.5 1.5 0 0 1 5 4a1.5 1.5 0 0 1 1.5-1.5m0 3V7l-3 3v9.5q0 .098.01.196q.009.098.028.194q.02.097.048.191q.029.094.066.184q.038.091.084.178q.046.086.101.168t.117.158t.132.145q.069.07.145.132t.158.117t.168.101q.087.046.178.084q.09.037.184.066q.094.028.191.048q.096.019.194.028t.196.01h6.429m2.571-8.101V10l-3-3V5.5m3.25 15.75l2.75-2.75a2.25 2.25 0 1 1 3-3a2.25 2.25 0 1 1-3 3");
}

</style>
