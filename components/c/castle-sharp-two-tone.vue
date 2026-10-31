<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="s9ocif-1s"/><path class="s8o59rb0o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:castle-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s8o59rb0o {
  d: path("M2 7L2 21L22 21L22 7M2 10L22 10M6 10L6 2M18 10L18 2M6 5L18 5M12 5L12 2M15 21L15 16.5C15 15.3954 13.1046 14 12 14C10.8954 14 9 15.3954 9 16.5L9 21");
}

.s9ocif-1s {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 9L22 9C22.5523 9 23 9.4477 23 10L23 21C23 21.5523 22.5523 22 22 22L2 22C1.4477 22 1 21.5523 1 21L1 10C1 9.4477 1.4477 9 2 9L5 9L5 5C5 4.4477 5.4477 4 6 4L18 4C18.5523 4 19 4.4477 19 5L19 9Z");
  stroke: none;
}

</style>
