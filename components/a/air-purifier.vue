<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="kjyo-to4o"/><circle class="pei_pcr2y"/><path class="vyyejfj4b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:air-purifier" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kjyo-to4o {
  width: 12.5px;
  height: 11.75px;
  x: 5.75px;
  y: 9.5px;
  rx: 3px;
}

.pei_pcr2y {
  cx: 12px;
  cy: 15.375px;
  r: 2.75px;
}

.vyyejfj4b {
  d: path("M7.75 3.5c1.4 1 2.85-1 4.25 0s2.85 1 4.25 0m-8.5 3c1.4 1 2.85-1 4.25 0s2.85 1 4.25 0");
}

</style>
