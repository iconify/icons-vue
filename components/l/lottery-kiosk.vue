<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yc8jn8g7v"/><path class="lga5qfbbv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lottery-kiosk" /></template>
<style>
.lga5qfbbv {
  d: path("M9.5 9h5l-3 6.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yc8jn8g7v {
  d: path("M3 6h18v3.5a2.5 2.5 0 0 0 0 5V18H3v-3.5a2.5 2.5 0 0 0 0-5Z");
}

</style>
