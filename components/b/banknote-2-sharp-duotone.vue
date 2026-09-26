<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="erfafodnh"/><path class="l7hxf_7ze"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:banknote-2-sharp-duotone" /></template>
<style>
.erfafodnh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 19C23 19.5523 22.5523 20 22 20L2 20C1.4477 20 1 19.5523 1 19L1 5C1 4.4477 1.4477 4 2 4L22 4C22.5523 4 23 4.4477 23 5L23 19Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.l7hxf_7ze {
  d: path("M14 12C14 13.1046 13.1046 14 12 14C10.8954 14 10 13.1046 10 12C10 10.8954 10.8954 10 12 10C13.1046 10 14 10.8954 14 12ZM18 4L18 5C18 6.3333 18.8 9 22 9L23 9M18 20L18 19C18 17.6667 18.8 15 22 15L23 15M6 20L6 19C6 17.6667 5.2 15 2 15L1 15M6 4L6 5C6 6.3333 5.2 9 2 9L1 9");
}

</style>
