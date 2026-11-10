<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="mgcqavsie"/><path class="rr_bwfbos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:house-play-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.mgcqavsie {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.454 2.15C11.796 1.97 12.296 1.96 12.61 2.2L20.628 8.37L23 10.38L21.707 11.91L21 11.31V21C21 21.55 20.552 22 20 22H4C3.448 22 3 21.55 3 21V11.31L2.293 11.91L1 10.38L3.372 8.37L11.454 2.15Z");
  stroke: none;
}

.rr_bwfbos {
  d: path("M22.352 11.15L19.998 9.15L11.998 3L3.998 9.15L1.645 11.15M3.998 9.15V21H19.998V9.15M9.498 9.28L15.874 13.5L9.498 17.72V9.28Z");
}

</style>
