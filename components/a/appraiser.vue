<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2a66ld3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:appraiser" /></template>
<style>
.g2a66ld3f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0M4 21c0-3.98 3.466-6.475 7.934-6.5m4.066 0h1.879a1.5 1.5 0 0 1 1.06.439l1.75 1.75a1.5 1.5 0 0 1 0 2.122l-1.878 1.878a1.5 1.5 0 0 1-2.122 0l-1.75-1.75a1.5 1.5 0 0 1-.439-1.06V16a1.5 1.5 0 0 1 1.5-1.5m.75 2.25h.01");
}

</style>
