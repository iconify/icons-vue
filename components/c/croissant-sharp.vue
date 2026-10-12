<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6yfthblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:croissant-sharp" /></template>
<style>
.y6yfthblv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 16.5C2.75 10.75 7 6.25 12 6.25s9.25 4.5 8.5 10.25l-.21 1.575L19 17l-3-2.5l-1.75 1.75h-4.5L8 14.5L5 17l-1.29 1.075zm5.75-8.25L10 13.5m4.75-5.25L14 13.5");
}

</style>
