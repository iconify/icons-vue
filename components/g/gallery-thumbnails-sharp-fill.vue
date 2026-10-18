<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ktz4dybai"/><path class="bxpilfbgv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gallery-thumbnails-sharp-fill" /></template>
<style>
.bxpilfbgv {
  d: path("M2 21L7 21M9.5 21L14.5 21M17 21L22 21");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ktz4dybai {
  fill: currentColor;
  d: path("M3 2L21 2C21.5523 2 22 2.4477 22 3L22 17C22 17.5523 21.5523 18 21 18L3 18C2.4477 18 2 17.5523 2 17L2 3C2 2.4477 2.4477 2 3 2Z");
  stroke: none;
}

</style>
