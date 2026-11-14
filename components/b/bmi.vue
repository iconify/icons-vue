<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="th56hjb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bmi" /></template>
<style>
.th56hjb6q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 19h18v2.5H3Zm9-10.75h1.75c1.25 0 2 .25 2.5 1.25l1.5 2.5c.5.75-.25 1.5-1 1.5c-.5 0-1-.5-1.25-1l-1-1.25L15 13l.5 4c.25.5 0 1-.75 1h-1c-.25 0-.75-.25-.75-.75L12.5 14c0-.5-1-.5-1 0l-.5 3.25c0 .5-.5.75-.75.75h-1c-.75 0-1-.5-.75-1l.5-4l.5-1.75l-1 1.25c-.25.5-.75 1-1.25 1c-.75 0-1.5-.75-1-1.5l1.5-2.5c.5-1 1.25-1.25 2.5-1.25ZM10.25 4a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

</style>
