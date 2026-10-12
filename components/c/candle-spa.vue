<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bpn7ngbby"/><rect class="obyjacb3x"/><path class="npjn27n1y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:candle-spa" /></template>
<style>
.bpn7ngbby {
  d: path("M12 2.75c1.4 1.5 2.2 2.7 2.2 3.85a2.2 2.2 0 0 1-4.4 0c0-1.15.8-2.35 2.2-3.85m0 7.5v2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.npjn27n1y {
  d: path("M4.75 16.25c2.4.9 4.8.9 7.25 0s4.85-.9 7.25 0");
}

.obyjacb3x {
  width: 14.5px;
  height: 8.25px;
  x: 4.75px;
  y: 13px;
  rx: 2.5px;
}

</style>
