<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzkb9z7yj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:aurora" /></template>
<style>
.tzkb9z7yj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7c3-3.5 6-3.5 9.25-1s6.25 2.5 9.25-1v4.5c-3 3.5-6 3.5-9.25 1s-6.25-2.5-9.25 1Zm0 13.35v-.45q0-.9.72-1.43l3.31-2.44q.72-.53 1.41.05l1.62 1.34q.69.58 1.51.21l2.86-1.26q.82-.37 1.61.07l4.67 2.62q.79.44.79 1.32q0 .87-.9.87H3.65q-.9 0-.9-.9");
}

</style>
