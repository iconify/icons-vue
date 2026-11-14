<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e4y6cmbbb"/><path class="li2rdbguz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camcorder" /></template>
<style>
.e4y6cmbbb {
  d: path("M6 8h6a3.5 3.5 0 0 1 3.5 3.5v4A3.5 3.5 0 0 1 12 19H6a3.5 3.5 0 0 1-3.5-3.5v-4A3.5 3.5 0 0 1 6 8m11.25 1.5h2.5a1.75 1.75 0 0 1 1.75 1.75v4.5a1.75 1.75 0 0 1-1.75 1.75h-2.5a1.75 1.75 0 0 1-1.75-1.75v-4.5a1.75 1.75 0 0 1 1.75-1.75m-11.5-6h3a1.75 1.75 0 0 1 1.75 1.75v1A1.75 1.75 0 0 1 8.75 8h-3A1.75 1.75 0 0 1 4 6.25v-1A1.75 1.75 0 0 1 5.75 3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.li2rdbguz {
  d: path("M7 13.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
