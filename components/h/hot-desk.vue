<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bd_1qj7az"/><rect class="vh84y-bdn"/><path class="ctwjpc5en"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hot-desk" /></template>
<style>
.bd_1qj7az {
  d: path("M7.25 4.75h9.5M15 3l1.75 1.75L15 6.5m1.75 3.75h-9.5M9 8.5l-1.75 1.75L9 12");
}

.ctwjpc5en {
  d: path("M5.5 18v3.25m13-3.25v3.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vh84y-bdn {
  width: 18.5px;
  height: 3px;
  x: 2.75px;
  y: 15px;
  rx: 1.5px;
}

</style>
