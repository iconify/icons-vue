<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wm8xwvb8g"/><path class="vawwjvb_h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:copy-image" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vawwjvb_h {
  d: path("M8.5 18.5L12 15l3.5 3.5m1-6h.01");
}

.wm8xwvb8g {
  d: path("M12.875 8.5h3.25a4.375 4.375 0 0 1 4.375 4.375v3.25a4.375 4.375 0 0 1-4.375 4.375h-3.25A4.375 4.375 0 0 1 8.5 16.125v-3.25A4.375 4.375 0 0 1 12.875 8.5M4 14.5V6a2.5 2.5 0 0 1 2.5-2.5h8");
}

</style>
