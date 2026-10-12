<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="djn6lybgu"/><circle class="rd87urb9k"/><path class="m4nplmbvh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:energy-meter" /></template>
<style>
.djn6lybgu {
  width: 16px;
  height: 18.5px;
  x: 4px;
  y: 2.75px;
  rx: 3px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m4nplmbvh {
  d: path("M12 9.75L14 8m-5.5 9.25h7");
}

.rd87urb9k {
  cx: 12px;
  cy: 9.75px;
  r: 4px;
}

</style>
