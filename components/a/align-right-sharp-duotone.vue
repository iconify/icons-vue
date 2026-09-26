<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="c8ot_ib-j"/><path class="uxhq29biw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-right-sharp-duotone" /></template>
<style>
.c8ot_ib-j {
  stroke-opacity: 0.4;
  d: path("M2 3L22 3M2 15L22 15");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uxhq29biw {
  d: path("M8 9L22 9M8 21L22 21");
}

</style>
