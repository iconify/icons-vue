<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f4xkz0b3b"/><path class="esol-1byo"/><path class="iy15zubxm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baby-shower" /></template>
<style>
.esol-1byo {
  d: path("M16.25 7.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0");
}

.f4xkz0b3b {
  d: path("M5.125 12h6.25A2.625 2.625 0 0 1 14 14.625v4.25a2.625 2.625 0 0 1-2.625 2.625h-6.25A2.625 2.625 0 0 1 2.5 18.875v-4.25A2.625 2.625 0 0 1 5.125 12m3.125 0c-2.75-4.5-5.25-.5 0 0c5.25-.5 2.75-4.5 0 0m0 0v9.5m3.25-16a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iy15zubxm {
  d: path("m14.5 8.5l3 7l1.5-5.25");
}

</style>
