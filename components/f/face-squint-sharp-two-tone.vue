<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="mcsmz_b3o"/><path class="gd0qfibhh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:face-squint-sharp-two-tone" /></template>
<style>
.gd0qfibhh {
  d: path("M8.14 7.2L8.5 7.5L10 8.75L8.5 10L8.14 10.3M15.86 7.2L15.5 7.5L14 8.75L15.5 10L15.86 10.3M22 12C22 17.523 17.523 22 12 22C6.477 22 2 17.523 2 12C2 6.477 6.477 2 12 2C17.523 2 22 6.477 22 12ZM8 14H16C16 16.209 14.209 18 12 18C9.791 18 8 16.209 8 14Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.mcsmz_b3o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19.778 4.222C21.768 6.211 23 8.963 23 12C23 18.075 18.075 23 12 23C5.925 23 1 18.075 1 12C1 5.925 5.925 1 12 1C15.037 1 17.789 2.232 19.778 4.222Z");
  stroke: none;
}

</style>
