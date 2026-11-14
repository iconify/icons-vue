<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8l38tbmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:category-office-furniture" /></template>
<style>
.h8l38tbmg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.125 2.25h3.75A2.625 2.625 0 0 1 15.5 4.875v4.25a2.625 2.625 0 0 1-2.625 2.625h-3.75A2.625 2.625 0 0 1 6.5 9.125v-4.25A2.625 2.625 0 0 1 9.125 2.25m-3.75 11h11.25A1.375 1.375 0 0 1 18 14.625A1.375 1.375 0 0 1 16.625 16H5.375A1.375 1.375 0 0 1 4 14.625a1.375 1.375 0 0 1 1.375-1.375M11 11.75v1.5M11 16v2.5m0 0l-8.5 1m8.5-1L6.5 21m4.5-2.5v3m0-3l4.5 2.5M11 18.5l8.5 1M18 13.25V9.5h2.5m-18 10h.01M6.5 21h.01m4.49.5h.01m4.49-.5h.01m3.99-1.5h.01");
}

</style>
