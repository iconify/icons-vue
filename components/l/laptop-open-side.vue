<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8mk4vbmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:laptop-open-side" /></template>
<style>
.p8mk4vbmj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.931 4.508zA1.5 1.5 0 0 1 5.75 5.601l2.298 9.218a1.5 1.5 0 0 1-1.093 1.818a1.5 1.5 0 0 1-1.818-1.092L2.839 6.327a1.5 1.5 0 0 1 1.092-1.819M5.25 17h13.5a1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75H5.25a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 5.25 17");
}

</style>
