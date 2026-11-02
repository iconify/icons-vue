<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xaza4v2nr"/><path class="se8yimb1k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cable-car-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.se8yimb1k {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 11h6a7.25 7.25 0 0 1 0 10H9a7.25 7.25 0 0 1 0-10m-2 5h10M4 9l16-4m-8 2v4m-2-7h.01M14 3h.01");
}

.xaza4v2nr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 10a1 1 0 0 1 .724.31a8.25 8.25 0 0 1 0 11.38A1 1 0 0 1 15 22H9a1 1 0 0 1-.724-.31a8.25 8.25 0 0 1 0-11.38A1 1 0 0 1 9 10Z");
}

</style>
