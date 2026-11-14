<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xq7mzwk9v"/><path class="njm63fbdb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cycling" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.njm63fbdb {
  d: path("M5.5 17L9 11l6 .5l3.5 5.5M9 11l4-3.5l2.5 3.5");
}

.xq7mzwk9v {
  d: path("M2 17a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m13 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M12 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
