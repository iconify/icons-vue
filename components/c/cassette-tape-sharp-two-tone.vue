<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="b2ps5cbvw"/><path class="t05-i6b9n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cassette-tape-sharp-two-tone" /></template>
<style>
.b2ps5cbvw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3L22 3C22.5523 3 23 3.4477 23 4L23 20C23 20.5523 22.5523 21 22 21L2 21C1.4477 21 1 20.5523 1 20L1 4C1 3.4477 1.4477 3 2 3Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t05-i6b9n {
  d: path("M2 4L22 4L22 20L2 20ZM10 10C10 11.1046 9.1046 12 8 12C6.8954 12 6 11.1046 6 10C6 8.8954 6.8954 8 8 8C9.1046 8 10 8.8954 10 10ZM18 10C18 11.1046 17.1046 12 16 12C14.8954 12 14 11.1046 14 10C14 8.8954 14.8954 8 16 8C17.1046 8 18 8.8954 18 10ZM8 12L16 12M6 20L7.4786 16.5L16.5214 16.5L18 20");
}

</style>
