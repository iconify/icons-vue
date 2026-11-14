<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yr_w4ibbv"/><path class="xz7xkzilc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cinema-loyalty-card" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xz7xkzilc {
  d: path("M4.75 14.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m5.75 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m5.75 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.yr_w4ibbv {
  d: path("M6.875 5h10.25A4.375 4.375 0 0 1 21.5 9.375v5.25A4.375 4.375 0 0 1 17.125 19H6.875A4.375 4.375 0 0 1 2.5 14.625v-5.25A4.375 4.375 0 0 1 6.875 5M2.5 9h19");
}

</style>
