<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inewv5bfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cursor-hand" /></template>
<style>
.inewv5bfs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 13.25V5a1.5 1.5 0 0 1 3 0v6.5a1.25 1.25 0 0 1 2.5 0a1.25 1.25 0 0 1 2.5 0a1.25 1.25 0 0 1 2.5 0v4c0 3.3-2 5.5-5 5.5h-1.25C11 21 9.9 20.3 9 19l-4-5.25a1.5 1.5 0 0 1 2-2Z");
}

</style>
