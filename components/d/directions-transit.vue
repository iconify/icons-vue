<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iybht3giq"/><path class="y28mpgbcg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:directions-transit" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iybht3giq {
  d: path("M8.875 2.5h6.25A4.375 4.375 0 0 1 19.5 6.875v7.25a4.375 4.375 0 0 1-4.375 4.375h-6.25A4.375 4.375 0 0 1 4.5 14.125v-7.25A4.375 4.375 0 0 1 8.875 2.5M7.5 18.5v3m9-3v3");
}

.y28mpgbcg {
  d: path("M9.25 5.5h5.5a1.75 1.75 0 0 1 1.75 1.75v2.5a1.75 1.75 0 0 1-1.75 1.75h-5.5A1.75 1.75 0 0 1 7.5 9.75v-2.5A1.75 1.75 0 0 1 9.25 5.5m-1 9.5h.01m7.49 0h.01");
}

</style>
