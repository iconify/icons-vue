<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yg3ibpb0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:charity-run" /></template>
<style>
.yg3ibpb0s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-.5 3.75l-2 5.75M5 9.5l3-1.75h3.5L14 10.5l3-1M4 17l3 .5l2.5-4L12 16l-1 4.5m7 .75c-2-1.25-3.25-2.5-3.25-4a1.625 1.625 0 0 1 3.25 0a1.625 1.625 0 0 1 3.25 0c0 1.5-1.25 2.75-3.25 4");
}

</style>
