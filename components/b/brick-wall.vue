<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="wg45x2bjw"/><path class="eue23_bxr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:brick-wall" /></template>
<style>
.eue23_bxr {
  d: path("M2.75 9.5h18.5m-18.5 5h18.5M12 4.25V9.5m-4.5 0v5m9-5v5m-4.5 0v5.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wg45x2bjw {
  width: 18.5px;
  height: 15.5px;
  x: 2.75px;
  y: 4.25px;
  rx: 2px;
}

</style>
