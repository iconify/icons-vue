<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="l5nx9bchx"/><path class="e7t2gybqd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:binoculars-sharp-two-tone" /></template>
<style>
.e7t2gybqd {
  d: path("M4 8L2 18L2 20L7 20C7 18.3431 8.3431 17 10 17L10 8ZM5 8L5 4L9 4L9 8M20 8L22 18L22 20L17 20C17 18.3431 15.6569 17 14 17L14 8ZM19 8L19 4L15 4L15 8M10 10L14 10M14 14L10 14");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.l5nx9bchx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 14L11 17C11 17.5523 10.5523 18 10 18C8.8954 18 8 18.8954 8 20C8 20.5523 7.5523 21 7 21L2 21C1.4477 21 1 20.5523 1 20L1 18C1 17.9341 1.0065 17.8685 1.0194 17.8039L3.0194 7.8039C3.1129 7.3365 3.5233 7 4 7L4 4C4 3.4477 4.4477 3 5 3L9 3C9.5523 3 10 3.4477 10 4L10 7C10.5523 7 11 7.4477 11 8L11 10L13 10L13 8C13 7.4477 13.4477 7 14 7L14 4C14 3.4477 14.4477 3 15 3L19 3C19.5523 3 20 3.4477 20 4L20 7C20.4767 7 20.8871 7.3365 20.9806 7.8039L22.9806 17.8039C22.9935 17.8685 23 17.9342 23 18L23 20C23 20.5523 22.5523 21 22 21L17 21C16.4477 21 16 20.5523 16 20C16 18.8954 15.1046 18 14 18C13.4477 18 13 17.5523 13 17L13 14L11 14Z");
  stroke: none;
}

</style>
