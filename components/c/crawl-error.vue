<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijhv_-b-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crawl-error" /></template>
<style>
.ijhv_-b-e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.875 5.5h4.25A4.375 4.375 0 0 1 15.5 9.875v1.25a4.375 4.375 0 0 1-4.375 4.375h-4.25A4.375 4.375 0 0 1 2.5 11.125v-1.25A4.375 4.375 0 0 1 6.875 5.5M9 5.5v-3m-2.75 8h.01m5.49 0h.01m7.59 5.534l1.605 3.312a1.5 1.5 0 0 1-1.349 2.154h-3.212a1.5 1.5 0 0 1-1.349-2.154l1.605-3.312a1.5 1.5 0 0 1 2.7 0M18 18.5h.01");
}

</style>
