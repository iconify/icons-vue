<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ao2gcsqwp"/><path class="uhf267b6d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bars-progress-two-tone" /></template>
<style>
.ao2gcsqwp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 2L20 2C21.1046 2 22 2.8954 22 4L22 8C22 9.1046 21.1046 10 20 10L4 10C2.8954 10 2 9.1046 2 8L2 4C2 2.8954 2.8954 2 4 2ZM4 14L20 14C21.1046 14 22 14.8954 22 16L22 20C22 21.1046 21.1046 22 20 22L4 22C2.8954 22 2 21.1046 2 20L2 16C2 14.8954 2.8954 14 4 14Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uhf267b6d {
  d: path("M4 3L20 3C20.5523 3 21 3.4477 21 4L21 8C21 8.5523 20.5523 9 20 9L4 9C3.4477 9 3 8.5523 3 8L3 4C3 3.4477 3.4477 3 4 3ZM4 15L20 15C20.5523 15 21 15.4477 21 16L21 20C21 20.5523 20.5523 21 20 21L4 21C3.4477 21 3 20.5523 3 20L3 16C3 15.4477 3.4477 15 4 15ZM15 3L15 9M10 15L10 21");
}

</style>
