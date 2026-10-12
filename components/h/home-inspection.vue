<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m44f-sb9f"/><circle class="ygphxfbhc"/><path class="pmw3q5b0z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:home-inspection" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m44f-sb9f {
  d: path("M2.75 18.75v-9.2q0-1 .78-1.62l5.69-4.55q.78-.63 1.56 0l5.69 4.55q.78.62.78 1.62v.7a7 7 0 0 0-7 7v1.5q0 1-1 1h-5.5q-1 0-1-1");
}

.pmw3q5b0z {
  d: path("m15.5 17.25l1.25 1.25L19 16");
}

.ygphxfbhc {
  cx: 17.25px;
  cy: 17.25px;
  r: 4px;
}

</style>
