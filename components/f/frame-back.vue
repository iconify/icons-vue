<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="xbn7f4blr"/><path class="f306-y_-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:frame-back" /></template>
<style>
.f306-y_-p {
  d: path("M9.25 8.25h12m-12 7.5h12m-15-7.25L2.75 12l3.5 3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xbn7f4blr {
  width: 12px;
  height: 14.5px;
  x: 9.25px;
  y: 4.75px;
  rx: 2px;
}

</style>
