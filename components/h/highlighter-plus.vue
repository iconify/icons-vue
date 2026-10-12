<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jyn29hl3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:highlighter-plus" /></template>
<style>
.jyn29hl3p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m19.89 6.93l-2.82-2.82q-.71-.71-1.42 0l-5.12 5.12q-.71.71-1.12 1.62l-.95 2.07q-.41.91-.09 1.86l.42 1.28q.32.95 1.19.45l3.21-1.83q.87-.5 1.58-1.21l5.12-5.12q.71-.71 0-1.42m-5.83 7.25L9.82 9.94M3.75 20.25h9");
}

</style>
