<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mcsmz_b3o"/><path class="muwbtv74s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:face-squint-two-tone" /></template>
<style>
.mcsmz_b3o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19.778 4.222C21.768 6.211 23 8.963 23 12C23 18.075 18.075 23 12 23C5.925 23 1 18.075 1 12C1 5.925 5.925 1 12 1C15.037 1 17.789 2.232 19.778 4.222Z");
  stroke: none;
}

.muwbtv74s {
  d: path("M8.5 7.5L10 8.75L8.5 10M15.5 7.5L14 8.75L15.5 10M22 12C22 17.523 17.523 22 12 22C6.477 22 2 17.523 2 12C2 6.477 6.477 2 12 2C17.523 2 22 6.477 22 12ZM9.171 14H14.829C15.518 14 16.001 14.682 15.772 15.332C15.212 16.919 13.707 18 12 18C10.293 18 8.788 16.919 8.228 15.332C7.999 14.682 8.482 14 9.171 14Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
