<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yh9w8vbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:deep-cleaning" /></template>
<style>
.yh9w8vbzs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 4c-2-2-7-2.5-7 3c0 3.5 1.5 5 2.25 7.5l1 4c.25 1 1.5 1 1.75 0l1-4.5c.25-1 1.75-1 2 0l1 4.5c.25 1 1.5 1 1.75 0l1-4C15 12 16.5 10.5 16.5 7c0-5.5-5-5-7-3ZM19 16q.5 2.5 3 3q-2.5.5-3 3q-.5-2.5-3-3q2.5-.5 3-3Z");
}

</style>
