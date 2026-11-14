<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d7ykymbfa"/><path class="s5ed8hbxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cash-detector" /></template>
<style>
.d7ykymbfa {
  d: path("M5.125 12h13.75a2.625 2.625 0 0 1 2.625 2.625v4.25a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 18.875v-4.25A2.625 2.625 0 0 1 5.125 12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s5ed8hbxf {
  d: path("M10 16.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0M12 3.5v5m-6.5-4l2 4m11-4l-2 4m-14-1.25l2 2m17-2l-2 2");
}

</style>
