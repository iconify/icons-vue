<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ped7-i-ni"/><path class="y42_9ybav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:event-feedback" /></template>
<style>
.ped7-i-ni {
  d: path("M6.5 17.5a8.5 8.5 0 1 0-2-2.5l-1.25 5.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y42_9ybav {
  d: path("m12 6.75l1.25 2.75l2.75.25l-2 1.75l.5 3L12 13l-2.5 1.5l.5-3l-2-1.75l2.75-.25Z");
}

</style>
