<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ucjxomb2w"/><path class="e_s5fwb-j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:light-switch" /></template>
<style>
.e_s5fwb-j {
  d: path("M11.625 6.5h.75A2.625 2.625 0 0 1 15 9.125v5.75a2.625 2.625 0 0 1-2.625 2.625h-.75A2.625 2.625 0 0 1 9 14.875v-5.75A2.625 2.625 0 0 1 11.625 6.5M9.25 12h5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ucjxomb2w {
  d: path("M8.375 3.5h7.25A4.375 4.375 0 0 1 20 7.875v8.25a4.375 4.375 0 0 1-4.375 4.375h-7.25A4.375 4.375 0 0 1 4 16.125v-8.25A4.375 4.375 0 0 1 8.375 3.5");
}

</style>
