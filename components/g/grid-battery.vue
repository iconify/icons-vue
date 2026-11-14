<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wpvqhgxxz"/><path class="mobnzkbbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:grid-battery" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mobnzkbbn {
  d: path("m16.25 8l-2 4h3l-2 4");
}

.wpvqhgxxz {
  d: path("M5.125 6h13.75A2.625 2.625 0 0 1 21.5 8.625v6.75A2.625 2.625 0 0 1 18.875 18H5.125A2.625 2.625 0 0 1 2.5 15.375v-6.75A2.625 2.625 0 0 1 5.125 6M6.5 9v6M10 9v6");
}

</style>
