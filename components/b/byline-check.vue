<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipx4oj79c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:byline-check" /></template>
<style>
.ipx4oj79c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m-2 12c0-3.5 2.5-5.5 5.5-5.5c1.773 0 3.371.698 4.382 1.992M16.5 10h5m-6.75 8l2 2L21 15.75");
}

</style>
