<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="d7ogp7fuy"/><path class="ffc3q8bwt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ev-charger-sharp-two-tone" /></template>
<style>
.d7ogp7fuy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M2 1L14 1C14.5523 1 15 1.4477 15 2L15 22C15 22.5523 14.5523 23 14 23L2 23C1.4477 23 1 22.5523 1 22L1 2C1 1.4477 1.4477 1 2 1ZM18 5L22 5C22.5523 5 23 5.4477 23 6L23 10C23 10.5523 22.5523 11 22 11L18 11C17.4477 11 17 10.5523 17 10L17 6C17 5.4477 17.4477 5 18 5Z");
  stroke: none;
}

.ffc3q8bwt {
  d: path("M2 2L14 2L14 22L2 22ZM14 22L23 22M14 17L20 17L20 10M18 6L22 6L22 10L18 10ZM22 6L22 3M18 6L18 3M9.3 7.6L6 12L10 12L6.7 16.4");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
