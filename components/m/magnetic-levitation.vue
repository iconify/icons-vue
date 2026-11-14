<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gd86mgblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:magnetic-levitation" /></template>
<style>
.gd86mgblf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 4h5A2.5 2.5 0 0 1 17 6.5A2.5 2.5 0 0 1 14.5 9h-5A2.5 2.5 0 0 1 7 6.5A2.5 2.5 0 0 1 9.5 4M5.25 16h13.5A2.25 2.25 0 0 1 21 18.25a2.25 2.25 0 0 1-2.25 2.25H5.25A2.25 2.25 0 0 1 3 18.25A2.25 2.25 0 0 1 5.25 16M12 4v5m-3 3.5h6");
}

</style>
