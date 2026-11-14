<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3k6pnb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dental-3d-print" /></template>
<style>
.p3k6pnb-h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 2.5h9v4h-9Zm3 4l1.5 2l1.5-2Zm1.5 6c-1.25-1-4.25-1.5-4.25 2c0 2 1 3 1.5 4.5l.5 2.25c.25.5 1 .5 1 0l.75-2.75c0-.5 1-.5 1 0l.75 2.75c0 .5.75.5 1 0l.5-2.25c.5-1.5 1.5-2.5 1.5-4.5c0-3.5-3-3-4.25-2Zm-3.75 3.25h7.5");
}

</style>
