<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkxr0kb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lead-scoring-ai" /></template>
<style>
.bkxr0kb-s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11a8 8 0 0 1 16 0m-8 0l4-4.5m-4 4.5h.01M18 14.5c.25 2.25 1.25 3.25 3.5 3.5c-2.25.25-3.25 1.25-3.5 3.5c-.25-2.25-1.25-3.25-3.5-3.5c2.25-.25 3.25-1.25 3.5-3.5");
}

</style>
