<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ns2olxb-s"/><path class="ehwu-cb2l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:castle-two-tone" /></template>
<style>
.ehwu-cb2l {
  d: path("M2 8L2 19C2 20.1046 2.8954 21 4 21L20 21C21.1046 21 22 20.1046 22 19L22 8M2 10L22 10M6 10L6 3M18 10L18 3M6 5L18 5M12 5L12 3M15 21L15 16.5C15 15.3954 13.1046 14 12 14C10.8954 14 9 15.3954 9 16.5L9 21");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ns2olxb-s {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 9L22 9C22.5523 9 23 9.4477 23 10L23 19C23 20.6569 21.6569 22 20 22L4 22C2.3431 22 1 20.6569 1 19L1 10C1 9.4477 1.4477 9 2 9L5 9L5 5C5 4.4477 5.4477 4 6 4L18 4C18.5523 4 19 4.4477 19 5L19 9Z");
  stroke: none;
}

</style>
