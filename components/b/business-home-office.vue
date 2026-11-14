<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bsq5xgbnw"/><path class="uv-03jbid"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:business-home-office" /></template>
<style>
.bsq5xgbnw {
  d: path("M3.5 21V10L12 2.5l8.5 7.5v11");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uv-03jbid {
  d: path("M9.75 9.5h4.5A1.75 1.75 0 0 1 16 11.25v2A1.75 1.75 0 0 1 14.25 15h-4.5A1.75 1.75 0 0 1 8 13.25v-2A1.75 1.75 0 0 1 9.75 9.5M12 15v3m-5.75 0h11.5");
}

</style>
