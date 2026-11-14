<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isebnnzak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:esports-team" /></template>
<style>
.isebnnzak {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 7a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0ZM6.5 20c0-3.5 2.5-5.5 5.5-5.5q.324 0 .639.031M6.5 10.75a2 2 0 1 0-4 0a2 2 0 1 0 4 0ZM2.25 20.5c0-2.5 1-4.25 2.25-4.75m13-5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-1 4.75H20c1.25 0 2 1.25 2 3V20c0 1-1 1.5-1.75.75l-1-1h-2l-1 1c-.75.75-1.75.25-1.75-.75v-1.5c0-1.75.75-3 2-3Z");
}

</style>
