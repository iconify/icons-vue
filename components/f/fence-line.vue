<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mk6x08h8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fence-line" /></template>
<style>
.mk6x08h8x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 19.5V7.526a1.5 1.5 0 0 1 .329-.937L4 5.75a1.28 1.28 0 0 1 2 0l.671.839A1.5 1.5 0 0 1 7 7.526V19.5A1.5 1.5 0 0 1 5.5 21h-1A1.5 1.5 0 0 1 3 19.5m7 0V7.526a1.5 1.5 0 0 1 .329-.937L11 5.75a1.28 1.28 0 0 1 2 0l.671.839a1.5 1.5 0 0 1 .329.937V19.5a1.5 1.5 0 0 1-1.5 1.5h-1a1.5 1.5 0 0 1-1.5-1.5m7 0V7.526a1.5 1.5 0 0 1 .329-.937L18 5.75a1.28 1.28 0 0 1 2 0l.671.839a1.5 1.5 0 0 1 .329.937V19.5a1.5 1.5 0 0 1-1.5 1.5h-1a1.5 1.5 0 0 1-1.5-1.5m-10-9h3m4 0h3m-10 6h3m4 0h3");
}

</style>
