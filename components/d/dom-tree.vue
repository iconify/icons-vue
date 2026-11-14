<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4blz8brs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dom-tree" /></template>
<style>
.j4blz8brs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 2.5h2A2.5 2.5 0 0 1 9.5 5A2.5 2.5 0 0 1 7 7.5H5A2.5 2.5 0 0 1 2.5 5A2.5 2.5 0 0 1 5 2.5M14.75 9h4.5a2.25 2.25 0 0 1 2.25 2.25a2.25 2.25 0 0 1-2.25 2.25h-4.5a2.25 2.25 0 0 1-2.25-2.25A2.25 2.25 0 0 1 14.75 9m0 7.5h4.5a2.25 2.25 0 0 1 2.25 2.25A2.25 2.25 0 0 1 19.25 21h-4.5a2.25 2.25 0 0 1-2.25-2.25a2.25 2.25 0 0 1 2.25-2.25M6 7.5v11.25h6.5M6 11.25h6.5");
}

</style>
