<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xmm3srbki"/><path class="gcvv_rb-r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chevrons-down-to-line" /></template>
<style>
.gcvv_rb-r {
  d: path("M5.25 11.75L12 18.5l6.75-6.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xmm3srbki {
  d: path("M5.25 5.5L12 12.25l6.75-6.75");
}

</style>
