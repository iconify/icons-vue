<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg852we3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:caddie" /></template>
<style>
.bg852we3o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 8a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-2 13.5V19a5 5 0 0 1 10 0v2.5M16 9h4.5v12.5H16Zm1 0l-1-5.5M19.5 9l1.25-5.5");
}

</style>
