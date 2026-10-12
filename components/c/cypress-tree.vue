<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fy9xkc-og"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cypress-tree" /></template>
<style>
.fy9xkc-og {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.86 17.99l.78-.23q.86-.26 1.31-1.04l.1-.19q.45-.78.16-1.63l-.02-.05q-.29-.85.04-1.69l.04-.07q.33-.84 0-1.68l-.04-.07q-.33-.84-.23-1.71q.1-.88-.27-1.7l-.06-.11q-.37-.82-.52-1.69q-.15-.88-.71-1.58l-.88-1.1q-.56-.7-1.12 0l-.88 1.1q-.56.7-.71 1.58q-.15.87-.52 1.69l-.06.11q-.37.82-.27 1.7q.1.87-.23 1.71l-.04.07q-.33.84 0 1.68l.04.07q.33.84.04 1.69l-.02.05q-.29.85.16 1.63l.1.19q.45.78 1.31 1.04l.78.23q.86.26 1.72 0m-.86.26v3m-2.5 0h5");
}

</style>
