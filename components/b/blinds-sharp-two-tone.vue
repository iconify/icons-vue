<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ylvrifbit"/><path class="q488d0b9r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:blinds-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q488d0b9r {
  d: path("M1 2L23 2M4 2L4 14L20 14L20 2M7 6L17 6M7 10L17 10M12 14L12 18M14 20C14 21.1046 13.1046 22 12 22C10.8954 22 10 21.1046 10 20C10 18.8954 10.8954 18 12 18C13.1046 18 14 18.8954 14 20Z");
}

.ylvrifbit {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 3.0001L21 14C21 14.5523 20.5523 15 20 15L4 15C3.4477 15 3 14.5523 3 14L3 3.0001L1 3.0001L1 1.0001L3.988 1.0001C3.992 1 3.996 1 4 1L20 1C20.004 1 20.008 1 20.012 1.0001L23 1.0001L23 3.0001L21 3.0001Z");
  stroke: none;
}

</style>
