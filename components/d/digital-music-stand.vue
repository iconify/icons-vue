<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gedhag35y"/><path class="w8e2vunyc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:digital-music-stand" /></template>
<style>
.gedhag35y {
  d: path("M6.625 2.5h10.75A2.625 2.625 0 0 1 20 5.125v7.25A2.625 2.625 0 0 1 17.375 15H6.625A2.625 2.625 0 0 1 4 12.375v-7.25A2.625 2.625 0 0 1 6.625 2.5M12 15v3l-4.5 3.5M12 18l4.5 3.5M13 5.25v5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w8e2vunyc {
  d: path("M10 10.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m3-5.5l2.5 1.25");
}

</style>
