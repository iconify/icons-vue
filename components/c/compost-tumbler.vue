<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_9rlywfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:compost-tumbler" /></template>
<style>
.q_9rlywfo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 7.5h13a1 1 0 0 1 1 1V15a1 1 0 0 1-1 1h-13a1 1 0 0 1-1-1V8.5a1 1 0 0 1 1-1Zm1.5 14L8 16m9 5.5L15 16m3.5-4.25H21V15M5.5 4.5q5.5-3 11 0M16 2l.5 2.5l-2.5.25");
}

</style>
