<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0zoi5bud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fencing-reel" /></template>
<style>
.i0zoi5bud {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10.5a2.5 7 0 1 0 5 0a2.5 7 0 1 0-5 0m14 0a2.5 7 0 1 0 5 0a2.5 7 0 1 0-5 0M7.25 7h9.5m-9.5 7h9.5M10.5 7v7m3-7v10q0 3 3 3h.5");
}

</style>
