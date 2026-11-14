<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fgjqqccuv"/><path class="owr1qcb3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:imu-sensor" /></template>
<style>
.fgjqqccuv {
  d: path("M5.75 18.25a8.75 8.75 0 1 1 12.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.owr1qcb3m {
  d: path("M18.25 15.75v2.5h2.5M10.688 8.5h2.625a2.19 2.19 0 0 1 2.187 2.188v2.625a2.19 2.19 0 0 1-2.187 2.187h-2.625A2.19 2.19 0 0 1 8.5 13.313v-2.625A2.19 2.19 0 0 1 10.688 8.5m-.188 0V7.25m3 1.25V7.25m-3 8.25v1.25m3-1.25v1.25m-5-6.25H7.25m1.25 3H7.25m8.25-3h1.25m-1.25 3h1.25");
}

</style>
