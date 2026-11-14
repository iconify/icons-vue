<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e38gqk76x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:consumer-group" /></template>
<style>
.e38gqk76x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 7.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm10 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM3 18c0-2.75 1.75-4.5 4-4.5s4 1.75 4 4.5m2.295-1.826C13.885 14.499 15.3 13.5 17 13.5h.03M21.5 19h-6m2.5-2.5L15.5 19l2.5 2.5");
}

</style>
