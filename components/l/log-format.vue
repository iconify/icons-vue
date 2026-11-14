<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d918qnbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:log-format" /></template>
<style>
.d918qnbjp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 5h18M3 10h14M3 15h8m5-1.25a1 1 0 0 0-1 1v2a1 1 0 0 1-1 1a1 1 0 0 1 1 1v2a1 1 0 0 0 1 1m4-8a1 1 0 0 1 1 1v2a1 1 0 0 0 1 1a1 1 0 0 0-1 1v2a1 1 0 0 1-1 1");
}

</style>
