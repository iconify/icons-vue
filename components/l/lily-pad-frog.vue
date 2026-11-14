<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lb5s94bec"/><path class="awm1lg0pl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lily-pad-frog" /></template>
<style>
.awm1lg0pl {
  d: path("M7 11.5c3 1.75 7 1.75 10 0m4.5 7.5c0 1.4-4.25 2.5-9.5 2.5S2.5 20.4 2.5 19s4.25-2.5 9.5-2.5c2.5 0 4.75.25 6.5.6L16 19Z");
}

.lb5s94bec {
  d: path("M5.75 6.5a2.75 2.75 0 1 1 5 0c.75.5 1.75.5 2.5 0a2.75 2.75 0 1 1 5 0c1.5 1 2.25 2.75 2.25 5c0 3.5-3.75 5-8.5 5s-8.5-1.5-8.5-5c0-2.25.75-4 2.25-5Zm2.5-1.25h.01m7.49 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
