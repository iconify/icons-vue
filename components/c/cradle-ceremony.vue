<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4-6rmfsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cradle-ceremony" /></template>
<style>
.b4-6rmfsw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 10h15v4a3 3 0 0 1-3 3h-9a3 3 0 0 1-3-3ZM3 18.5q9 4.5 18 0M4.5 10V8a4 4 0 0 1 8 0v2M8 17v3.25M16 17v3.25");
}

</style>
