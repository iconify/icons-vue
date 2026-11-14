<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qv2l24g1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:jade-plant" /></template>
<style>
.qv2l24g1i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 15h10l-1.25 6h-7.5Zm5 0V7.75M9.75 11L12 13.25L14.25 11m-4-6a1.75 2.75 0 1 0 3.5 0a1.75 2.75 0 1 0-3.5 0M4 9.5a3 1.75 0 1 0 6 0a3 1.75 0 1 0-6 0m10 0a3 1.75 0 1 0 6 0a3 1.75 0 1 0-6 0");
}

</style>
