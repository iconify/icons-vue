<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e397-0bbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:auditorium-sharp" /></template>
<style>
.e397-0bbx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.25h18.5V9.5H2.75zm2 8.25a26.8 26.8 0 0 0 14.5 0m-16.5 4a43.5 43.5 0 0 0 18.5 0");
}

</style>
