<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="qbcs2xgch"/><path class="uk-eumb3f"/><path class="aiist0mhp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-pound-sterling-sharp-two-tone" /></template>
<style>
.aiist0mhp {
  d: path("M10 19L10 18L10 8C10 6.8954 10.8954 6 12 6C13.1046 6 14 6.8954 14 8C14 8.3511 13.9076 8.696 13.7321 9L13.4434 9.5M7.5 14L8.5 14L14 14L15 14M7.5 18L8.5 18L15.5 18L16.5 18");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qbcs2xgch {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 1C17.9372 1 23 6.0628 23 12C23 17.9372 17.9372 23 12 23C6.0628 23 1 17.9372 1 12C1 6.0628 6.0628 1 12 1Z");
  stroke: none;
}

.uk-eumb3f {
  d: path("M12 2C17.523 2 22 6.477 22 12C22 17.523 17.523 22 12 22C6.477 22 2 17.523 2 12C2 6.477 6.477 2 12 2Z");
}

</style>
