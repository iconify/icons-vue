<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e75_ovw6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:last-mile-route" /></template>
<style>
.e75_ovw6w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 18a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m13-12a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m-8.5 12H13c3 0 3-6-1-6s-4-6-1-6h5.25");
}

</style>
