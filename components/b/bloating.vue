<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3vy-nbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bloating" /></template>
<style>
.v3vy-nbzr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 2.5C8.75 6 7 8.5 7 12.5s1.5 6.5 2 9m6.25-19c0 3.5 1.75 6 1.75 10s-1.5 6.5-2 9M12 13h.01m6.49-.5h3M20 11l1.5 1.5L20 14M5.5 12.5h-3M4 11l-1.5 1.5L4 14");
}

</style>
