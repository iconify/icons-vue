<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z00r_bblh"/><path class="zf6acx20s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:condo-tower" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z00r_bblh {
  d: path("M6.5 20.35V8.4q0-.9.7-1.46l1.1-.88Q9 5.5 9 4.6v-.95q0-.9.9-.9h4.2q.9 0 .9.9v.95q0 .9.7 1.46l1.1.88q.7.56.7 1.46v11.95q0 .9-.9.9H7.4q-.9 0-.9-.9M9.75 9.5v7m2.25-7v7m2.25-7v7");
}

.zf6acx20s {
  d: path("M10.5 21.25v-2.5h3v2.5");
}

</style>
