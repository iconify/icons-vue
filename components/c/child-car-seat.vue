<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6syj6bft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:child-car-seat" /></template>
<style>
.i6syj6bft {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 12a7 7 0 0 1 14 0M2.75 12h18.5l-1.4 6.6a3.4 3.4 0 0 1-3.3 2.65h-9.1a3.4 3.4 0 0 1-3.3-2.65Zm5 4.5h8.5");
}

</style>
