<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwaxx8bvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chapters-video" /></template>
<style>
.uwaxx8bvl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.113 4.981l2.2 1.246a1.75 1.75 0 0 1 0 3.046l-2.2 1.246A1.75 1.75 0 0 1 3.5 8.997V6.503a1.75 1.75 0 0 1 2.613-1.522M2.5 17h19M8.75 14.75v4.5m6.5-4.5v4.5");
}

</style>
