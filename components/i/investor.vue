<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="se6ixebfq"/><path class="gy6dhismv"/><rect class="uovspt0xi"/><path class="s-c365b4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:investor" /></template>
<style>
.gy6dhismv {
  d: path("M3.5 20.25h8a.75.75 0 0 0 .75-.75c0-3.62-2.17-6.25-4.75-6.25s-4.75 2.63-4.75 6.25a.75.75 0 0 0 .75.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s-c365b4c {
  d: path("M15.25 14h6m-6 3.5h6");
}

.se6ixebfq {
  cx: 7.5px;
  cy: 7.75px;
  r: 3.25px;
}

.uovspt0xi {
  width: 6px;
  height: 11px;
  x: 15.25px;
  y: 10.25px;
  rx: 2px;
}

</style>
