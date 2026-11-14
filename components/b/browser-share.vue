<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uy63i4skh"/><path class="bj54o4--d"/><path class="b-nob7xrl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:browser-share" /></template>
<style>
.b-nob7xrl {
  fill: currentColor;
  d: path("M12 14.25v-4.5a4.5 4.5 0 0 1 4.5 4.5Z");
}

.bj54o4--d {
  d: path("M7.5 14.25a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uy63i4skh {
  d: path("M6.875 2.5h10.25A4.375 4.375 0 0 1 21.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 17.125V6.875A4.375 4.375 0 0 1 6.875 2.5M2.5 6.75h19M5.5 4.5h.01M8 4.5h.01");
}

</style>
