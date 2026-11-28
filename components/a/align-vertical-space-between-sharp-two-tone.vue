<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ndu8bwbjz"/><path class="ol68zwbup"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-vertical-space-between-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ndu8bwbjz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 5V9C6 9.5523 6.4477 10 7 10H17C17.5523 10 18 9.5523 18 9V5H23V3H1V5ZM6 19V15C6 14.4477 6.4477 14 7 14H17C17.5523 14 18 14.4477 18 15V19H23V21H1V19Z");
  stroke: none;
}

.ol68zwbup {
  d: path("M1 20H23M1 4H23M7 4H17V9H7V4ZM7 15H17V20H7V15Z");
}

</style>
