<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aavg1tnmo"/><rect class="ijrtfzies"/><path class="fmlaifbpn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fleur-de-lis" /></template>
<style>
.aavg1tnmo {
  d: path("M12 2.75c1.5 2 2.25 4.25 2.25 6.5c0 2-1 3.25-2.25 4.75c-1.25-1.5-2.25-2.75-2.25-4.75c0-2.25.75-4.5 2.25-6.5M8.75 14c-.75-2.25-1.5-4-3-4.75C4.5 8.6 3 9.25 3 10.75c0 1 1 1.75 2 1.25m10.25 2c.75-2.25 1.5-4 3-4.75c1.25-.65 2.75 0 2.75 1.5c0 1-1 1.75-2 1.25");
}

.fmlaifbpn {
  d: path("M12 16v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ijrtfzies {
  width: 8px;
  height: 2px;
  x: 8px;
  y: 14px;
  rx: 0.5px;
}

</style>
