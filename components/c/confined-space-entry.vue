<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czx5v0t5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:confined-space-entry" /></template>
<style>
.czx5v0t5a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16.75a9.5 3.75 0 1 0 19 0a9.5 3.75 0 1 0-19 0m6.5 0h6M12 2.5V10M8.75 6.75L12 10l3.25-3.25");
}

</style>
