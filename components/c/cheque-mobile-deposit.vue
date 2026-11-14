<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bj2dwm-qe"/><path class="dxvw4cneg"/><path class="rfpnalb7x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cheque-mobile-deposit" /></template>
<style>
.bj2dwm-qe {
  d: path("M6.375 5h11.25A4.375 4.375 0 0 1 22 9.375v5.25A4.375 4.375 0 0 1 17.625 19H6.375A4.375 4.375 0 0 1 2 14.625v-5.25A4.375 4.375 0 0 1 6.375 5");
}

.dxvw4cneg {
  d: path("M8.25 7.75h8A1.75 1.75 0 0 1 18 9.5v5a1.75 1.75 0 0 1-1.75 1.75h-8A1.75 1.75 0 0 1 6.5 14.5v-5a1.75 1.75 0 0 1 1.75-1.75M9 10.5h3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rfpnalb7x {
  d: path("M11.5 13.5c.75-.75 1.25.5 2-.25c.5-.5 1 .5 2 .25M4.25 12h.01");
}

</style>
