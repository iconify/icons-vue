<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="e6d79qrxr"/><path class="tkp_8ackj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:inbox-sharp-two-tone" /></template>
<style>
.e6d79qrxr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 3L17 3C17.3478 3 17.6706 3.1807 17.8525 3.4772L22.8525 11.6306C22.9489 11.7879 23 11.9689 23 12.1534L23 20C23 20.5523 22.5523 21 22 21L2 21C1.4477 21 1 20.5523 1 20L1 12.1534C1 11.9689 1.0511 11.7879 1.1475 11.6306L6.1475 3.4772C6.3294 3.1807 6.6522 3 7 3Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tkp_8ackj {
  d: path("M7 4L17 4L22 12.1534L22 20L2 20L2 12.1534L7 4ZM2 13L8 13L10 16L14 16L16 13L22 13");
}

</style>
