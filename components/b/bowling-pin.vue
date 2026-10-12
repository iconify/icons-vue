<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7yj1yr2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bowling-pin" /></template>
<style>
.j7yj1yr2w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75c1.6 0 2.5 1.5 2.5 3.25c0 1.5-.9 2.5-.9 3.75c0 1.75 3.15 3.5 3.15 7.25c0 1.75-.5 3-1 4.25h-7.5c-.5-1.25-1-2.5-1-4.25c0-3.75 3.15-5.5 3.15-7.25c0-1.25-.9-2.25-.9-3.75c0-1.75.9-3.25 2.5-3.25m-1.5 7h3");
}

</style>
