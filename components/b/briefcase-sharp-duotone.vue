<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="qyiv18v2z"/><path class="i3ssdb-4p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:briefcase-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.i3ssdb-4p {
  d: path("M8.25 6.5L8.25 3L15.75 3L15.75 6.5M2 10.5C6 12.75 18 12.75 22 10.5M9.5 12.1132L9.5 15.5L14.5 15.5L14.5 12.1132");
}

.qyiv18v2z {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5.5L22 5.5C22.5523 5.5 23 5.9477 23 6.5L23 21C23 21.5523 22.5523 22 22 22L2 22C1.4477 22 1 21.5523 1 21L1 6.5C1 5.9477 1.4477 5.5 2 5.5Z");
  stroke: none;
}

</style>
