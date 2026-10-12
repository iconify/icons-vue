<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="w6czd5b3h"/><path class="j7bg-obal"/><path class="ye-rqim7m"/><rect class="vk76amrji"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:embroidery-hoop" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j7bg-obal {
  d: path("M17.5 13.25a5.5 5.5 0 1 1-11 0a5.5 5.5 0 1 1 11 0");
}

.vk76amrji {
  width: 3.5px;
  height: 2.5px;
  x: 10.25px;
  y: 2.75px;
  rx: 1px;
}

.w6czd5b3h {
  cx: 12px;
  cy: 13.25px;
  r: 8px;
}

.ye-rqim7m {
  d: path("M12 16c-1.5-.95-2.6-1.9-2.6-3a1.3 1.3 0 0 1 2.6-.4a1.3 1.3 0 0 1 2.6.4c0 1.1-1.1 2.05-2.6 3");
}

</style>
