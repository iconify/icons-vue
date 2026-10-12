<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="vxu-68t9g"/><path class="omi9uhb9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:calendar-download" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.omi9uhb9y {
  d: path("M8 2.75v3.5m8-3.5v3.5M2.75 9.75h18.5M12 18.5c-2.5-1.5-4-3-4-4.6c0-1.1.8-1.65 1.75-1.65c1 0 1.75.6 2.25 1.4c.5-.8 1.25-1.4 2.25-1.4c.95 0 1.75.55 1.75 1.65c0 1.6-1.5 3.1-4 4.6");
}

.vxu-68t9g {
  width: 18.5px;
  height: 16.5px;
  x: 2.75px;
  y: 4.75px;
  rx: 2.5px;
}

</style>
