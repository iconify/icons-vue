<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zpx_6t8ti"/><path class="i5nsu8bek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cloud-api" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i5nsu8bek {
  d: path("M10 12h-.5a1 1 0 0 0-1 1v.5a1 1 0 0 1-1 1a1 1 0 0 1 1 1v.5a1 1 0 0 0 1 1h.5m4-5h.5a1 1 0 0 1 1 1v.5a1 1 0 0 0 1 1a1 1 0 0 0-1 1v.5a1 1 0 0 1-1 1H14");
}

.zpx_6t8ti {
  d: path("M7 19a4 4 0 0 1 0-8a5.5 5.5 0 0 1 11 1a3.5 3.5 0 0 1-1 7Z");
}

</style>
