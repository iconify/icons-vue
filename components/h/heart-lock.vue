<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x1fdkmynh"/><path class="drg8g9bbi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heart-lock" /></template>
<style>
.drg8g9bbi {
  d: path("M12 18.75L9.25 16A2 2 0 0 1 12 13.5a2 2 0 0 1 2.75 2.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x1fdkmynh {
  d: path("M8.375 10h7.25A4.375 4.375 0 0 1 20 14.375v2.75a4.375 4.375 0 0 1-4.375 4.375h-7.25A4.375 4.375 0 0 1 4 17.125v-2.75A4.375 4.375 0 0 1 8.375 10M7.5 10V7a4.5 4.5 0 0 1 9 0v3");
}

</style>
