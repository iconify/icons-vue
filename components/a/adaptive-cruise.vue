<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aau69305a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:adaptive-cruise" /></template>
<style>
.aau69305a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 14l2-4.5q.5-1 1.5-1h10q1 0 1.5 1l2 4.5v7h-3v-1.5h-11V21h-3Zm0 0h17M7 16.75h.01m9.99 0h.01M7 5.5q5-4 10 0");
}

</style>
