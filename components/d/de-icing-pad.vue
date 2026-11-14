<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5rbf6bap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:de-icing-pad" /></template>
<style>
.j5rbf6bap {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 2.5v16m-7-12l12.242 6.996M3.5 14.5l14-8M8.25 4.25L10.5 5.5l2.25-1.25m2 1.25V8L17 9.25m0 2.5L14.75 13v1.726m-2 2.024L10.5 15.5l-2.25 1.25m-2-1.25V13L4 11.75m0-2.5L6.25 8V5.5m12.25 9c1 1.5 3 3.25 3 4.5a3 3 0 0 1-6 0c0-1.25 2-3 3-4.5");
}

</style>
