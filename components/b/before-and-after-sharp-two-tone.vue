<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ffaj2xnln"/><path class="xnp8rvb7l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:before-and-after-sharp-two-tone" /></template>
<style>
.ffaj2xnln {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 12L11 19C11 19.5523 11.4477 20 12 20L22 20C22.5523 20 23 19.5523 23 19L23 5C23 4.4477 22.5523 4 22 4L12 4C11.4477 4 11 4.4477 11 5Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xnp8rvb7l {
  d: path("M12 5L22 5L22 19L12 19M9 19L8 19L2 19L2 5L8 5L9 5M12 23L12 22L12 19L12 5L12 2L12 1");
}

</style>
