<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1lxbzrbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:clapperboard" /></template>
<style>
.e1lxbzrbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 9.5h11A3.5 3.5 0 0 1 21 13v4a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 17v-4a3.5 3.5 0 0 1 3.5-3.5M2.896 7.85l-.021-.1a1.726 1.726 0 0 1 1.387-2.061l13.576-2.396a1.75 1.75 0 0 1 2.016 1.357l.021.1a1.726 1.726 0 0 1-1.387 2.061L4.912 9.207A1.75 1.75 0 0 1 2.896 7.85m5.354-3.1L10 8.25m3.5-4.5l1.75 3.5");
}

</style>
