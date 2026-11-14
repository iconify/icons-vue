<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fr017jbmr"/><path class="wbrlqh56d"/><path class="i2ptecbdr"/><path class="qycj39xxt"/><path class="dj2ytohhv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:atomic-swap" /></template>
<style>
.dj2ytohhv {
  d: path("M3.25 16.75L5 15l1.75 1.75");
}

.fr017jbmr {
  d: path("M7 2.5L11.25 5v4.75L7 12.25l-4.25-2.5V5Z");
}

.i2ptecbdr {
  d: path("m12.75 14.25l4.25 2.5l4.25-2.5M17 16.75v4.75m-2.5-17H17a2 2 0 0 1 2 2V9");
}

.qycj39xxt {
  d: path("M17.25 7.25L19 9l1.75-1.75M9.5 19.5H7a2 2 0 0 1-2-2V15");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wbrlqh56d {
  d: path("M2.75 5L7 7.5L11.25 5M7 7.5v4.75m10-.5l4.25 2.5V19L17 21.5L12.75 19v-4.75Z");
}

</style>
