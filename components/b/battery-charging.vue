<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="y6nr_abgb"/><path class="nhv384bfz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:battery-charging" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nhv384bfz {
  d: path("M21.25 10.5v3M11.75 9l-2.5 3.25h4.5l-2.5 3.25");
}

.y6nr_abgb {
  width: 16px;
  height: 10.5px;
  x: 2.75px;
  y: 6.75px;
  rx: 2.5px;
}

</style>
