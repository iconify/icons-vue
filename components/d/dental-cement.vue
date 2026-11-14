<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_js2acgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dental-cement" /></template>
<style>
.y_js2acgr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.5H12l5 2.25v1.5L12 9.5H3.5Zm8.5 9c-1.5 0-2.5 1-2.5 2.5s1 2.5 1.5 4l.5 2c.25.75 1.25.75 1.5 0l.75-2.5c.25-.5.75-.75 1.25-.75s1 .25 1.25.75L17 21c.25.75 1.25.75 1.5 0l.5-2c.5-1.5 1.5-2.5 1.5-4s-1-2.5-2.5-2.5c-1 0-2 .5-3 .5s-2-.5-3-.5m5-6q2.5 0 2.5 2.5T17 12.5");
}

</style>
