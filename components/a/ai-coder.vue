<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="x4hlzsk-k"/><path class="w6jczwbbd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ai-coder" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w6jczwbbd {
  d: path("M2.75 19.25h18.5M9.75 7.75l-2 2l2 2m4.5-4l2 2l-2 2");
}

.x4hlzsk-k {
  width: 15.5px;
  height: 11px;
  x: 4.25px;
  y: 4.25px;
  rx: 2px;
}

</style>
