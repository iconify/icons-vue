<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="dpkficrzl"/><path class="ya7yz-bii"/><path class="vimlx0z5q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fire-truck-sharp-duotone" /></template>
<style>
.dpkficrzl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18.5 5L19 5C19.3513 5 19.6768 5.1843 19.8575 5.4855L22.8575 10.4855C22.9507 10.6409 23 10.8188 23 11L23 18C23 18.5523 22.5523 19 22 19L16 19L2 19C1.4477 19 1 18.5523 1 18L1 10C1 9.4477 1.4477 9 2 9L9 9L15 9L15 6C15 5.4477 15.4477 5 16 5L16.5 5L16.5 4L16.5 3L18.5 3L18.5 4Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vimlx0z5q {
  d: path("M1 6L2 6L12 6L12 10M4 6L4 10M8 6L8 10M9 18C9 19.1046 8.1046 20 7 20C5.8954 20 5 19.1046 5 18C5 16.8954 5.8954 16 7 16C8.1046 16 9 16.8954 9 18ZM19 18C19 19.1046 18.1046 20 17 20C15.8954 20 15 19.1046 15 18C15 16.8954 15.8954 16 17 16C18.1046 16 19 16.8954 19 18Z");
}

.ya7yz-bii {
  fill: currentColor;
  d: path("M19 11L17 11L17 7L18.4338 7L20.8338 11Z");
  stroke: none;
}

</style>
