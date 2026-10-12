<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sjp7vw1zt"/><rect class="x0azt-b-t"/><path class="elfxldbbl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hacksaw" /></template>
<style>
.elfxldbbl {
  d: path("M3.5 13.5h13.25m-10.25 0V15m3-1.5V15m3-1.5V15");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sjp7vw1zt {
  d: path("M3.5 16.5V6a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v6.5");
}

.x0azt-b-t {
  width: 4.5px;
  height: 8.75px;
  x: 16.75px;
  y: 12.5px;
  rx: 2px;
}

</style>
