<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ox05rfewb"/><path class="xdmvhuwpq"/><path class="z4w9axbqd"/><path class="bsc54w4zs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:alarm-panel-sharp" /></template>
<style>
.bsc54w4zs {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 15.75h3");
}

.ox05rfewb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4.75h18.5v14.5H2.75z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xdmvhuwpq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 7.75h6.5v4.5h-6.5z");
}

.z4w9axbqd {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 8.25h.01m2.99 0h.01M15 12h.01M18 12h.01M15 15.75h.01m2.99 0h.01");
}

</style>
