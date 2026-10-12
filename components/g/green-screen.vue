<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="prgd5lb5c"/><circle class="r-vnokzof"/><path class="xes36ab-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:green-screen" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.prgd5lb5c {
  width: 18.5px;
  height: 14px;
  x: 2.75px;
  y: 2.75px;
  rx: 2px;
}

.r-vnokzof {
  cx: 12px;
  cy: 7.5px;
  r: 2.25px;
}

.xes36ab-a {
  d: path("M7.5 16.75a4.5 4.5 0 0 1 9 0Zm-2.75 0l-1.25 4.5m15.75-4.5l1.25 4.5");
}

</style>
