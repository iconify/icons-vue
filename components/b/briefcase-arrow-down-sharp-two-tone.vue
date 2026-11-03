<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="dy_m-wdqa"/><path class="ttu6qnbom"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:briefcase-arrow-down-sharp-two-tone" /></template>
<style>
.dy_m-wdqa {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16.5 5L21 5C21.5523 5 22 5.4477 22 6L22 18C22 18.5523 21.5523 19 21 19L3 19C2.4477 19 2 18.5523 2 18L2 6C2 5.4477 2.4477 5 3 5L7.5 5L7.5 2C7.5 1.4477 7.9477 1 8.5 1L15.5 1C16.0523 1 16.5 1.4477 16.5 2L16.5 5Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ttu6qnbom {
  d: path("M12 9L12 14M8.7071 10.7071L12 14L15.2929 10.7071M2 22L22 22M8.5 6L3 6L3 18L21 18L21 6L15.5 6M8.5 6L8.5 2L15.5 2L15.5 6M8.5 6L15.5 6");
}

</style>
