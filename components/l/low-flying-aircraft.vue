<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krcjzhq0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:low-flying-aircraft" /></template>
<style>
.krcjzhq0h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.5 10c0-.75-.75-1.25-1.5-1.25h-5L9 3.5H7l2.25 5.25H5.5L4 7H2.5l.75 3l-.75 3H4l1.5-1.75h3.75L7 16.5h2l4-5.25h5c.75 0 1.5-.5 1.5-1.25M18 14.5v7m-3-3l3 3l3-3");
}

</style>
