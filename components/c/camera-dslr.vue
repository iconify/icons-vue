<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pe3mktc2h"/><circle class="fv8wiubss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:camera-dslr" /></template>
<style>
.fv8wiubss {
  cx: 11px;
  cy: 14.25px;
  r: 3px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pe3mktc2h {
  d: path("M4 8h2.75Q8 8 8.3 6.79l.65-2.58Q9.25 3 10.5 3h1q1.25 0 1.55 1.21l.65 2.58Q14 8 15.25 8h2q1.25 0 1.25.63q0 .62 1.25.62H20q1.25 0 1.25 1.25V19q0 1.25-1.25 1.25H4q-1.25 0-1.25-1.25V9.25Q2.75 8 4 8");
}

</style>
