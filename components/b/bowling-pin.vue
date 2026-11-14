<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zw35xyb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bowling-pin" /></template>
<style>
.zw35xyb3h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 21.5h4.5c2.25-3.5 2.5-7.5-.25-11c-.75-1 1-2 1-5a3 3 0 0 0-6 0c0 3 1.75 4 1 5c-2.75 3.5-2.5 7.5-.25 11m.25-11h4");
}

</style>
