<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="p53xcyb3q"/><path class="xwaric7fy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-bar-big-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p53xcyb3q {
  stroke-opacity: 0.4;
  d: path("M3 2L3 21L22 21");
}

.xwaric7fy {
  fill: currentColor;
  d: path("M7 4L16 4C16.5523 4 17 4.4477 17 5L17 9C17 9.5523 16.5523 10 16 10L7 10C6.4477 10 6 9.5523 6 9L6 5C6 4.4477 6.4477 4 7 4ZM7 12L19 12C19.5523 12 20 12.4477 20 13L20 17C20 17.5523 19.5523 18 19 18L7 18C6.4477 18 6 17.5523 6 17L6 13C6 12.4477 6.4477 12 7 12Z");
  stroke: none;
}

</style>
