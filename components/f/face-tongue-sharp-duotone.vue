<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="cwinfwbnk"/><path class="uxp4afb5b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:face-tongue-sharp-duotone" /></template>
<style>
.cwinfwbnk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19.7782 4.2218C21.7677 6.2114 23 8.9627 23 12C23 18.0751 18.0751 23 12 23C5.9249 23 1 18.0751 1 12C1 5.9249 5.9249 1 12 1C15.0373 1 17.7886 2.2323 19.7782 4.2218Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uxp4afb5b {
  d: path("M9 7L9 10M13 8.5L17 8.5M7 13L17 13M10 13L10 16C10 17.1046 10.8954 18 12 18C13.1046 18 14 17.1046 14 16L14 13");
}

</style>
