<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ei1owcwdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hair-oil" /></template>
<style>
.ei1owcwdo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 7V4.5a2 2 0 0 1 4 0V7M6.5 7h7v3h-7Zm7.2 14.5H4V10h12v2.1m2.5 1.4s2.75 3 2.75 5.25a2.75 2.75 0 0 1-5.5 0c0-2.25 2.75-5.25 2.75-5.25Z");
}

</style>
