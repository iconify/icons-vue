<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r50m1k6ci"/><path class="frtykac3b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:employee-birthday" /></template>
<style>
.frtykac3b {
  d: path("M4.5 15.5c2.5 2 3.5-2 7.5 0s5-2 7.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r50m1k6ci {
  d: path("M8 11h8a3.5 3.5 0 0 1 3.5 3.5V17a3.5 3.5 0 0 1-3.5 3.5H8A3.5 3.5 0 0 1 4.5 17v-2.5A3.5 3.5 0 0 1 8 11m4 0V8m0 0c-1.5-1.5-.75-3.5 0-4.5c.75 1 1.5 3 0 4.5");
}

</style>
