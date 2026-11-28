<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="a0nm-s25d"/><path class="jpo7_pb2a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:baseline-sharp-duotone" /></template>
<style>
.a0nm-s25d {
  stroke-opacity: 0.4;
  d: path("M5.7402 17.6061L12 3L18.2598 17.6061M7.7131 13L16.2869 13");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jpo7_pb2a {
  d: path("M2 21L22 21");
}

</style>
