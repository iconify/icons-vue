<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="j66bxbuam"/><path class="flib4x-wn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lipstick-sharp-two-tone" /></template>
<style>
.flib4x-wn {
  d: path("M16 14L16 5.385L8 2.0013L8 15L6 15L6 22L18 22L18 15L16 15ZM16 11L8 11");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.j66bxbuam {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 8.5007L7 2.0013C7 1.449 7.4477 1.0013 8 1.0013C8.1338 1.0013 8.2663 1.0282 8.3896 1.0803L16.3896 4.464C16.7596 4.6205 17 4.9832 17 5.385L17 14L18 14C18.5523 14 19 14.4477 19 15L19 22C19 22.5523 18.5523 23 18 23L6 23C5.4477 23 5 22.5523 5 22L5 15C5 14.4477 5.4477 14 6 14L7 14Z");
  stroke: none;
}

</style>
