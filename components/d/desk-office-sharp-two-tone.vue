<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="y_aqquhxs"/><path class="a69icf1xn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:desk-office-sharp-two-tone" /></template>
<style>
.a69icf1xn {
  d: path("M3 23L3 12L21 12L21 22L14 22L14 11M21 17L14 17M12 12L12 8M7 8L7 2L17 2L17 8L7 8Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y_aqquhxs {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M14 11L21 11C21.5523 11 22 11.4477 22 12L22 22C22 22.5523 21.5523 23 21 23L14 23C13.4477 23 13 22.5523 13 22L13 12C13 11.4477 13.4477 11 14 11ZM6 8L6 2C6 1.4477 6.4477 1 7 1L17 1C17.5523 1 18 1.4477 18 2L18 8C18 8.5523 17.5523 9 17 9L7 9C6.4477 9 6 8.5523 6 8Z");
  stroke: none;
}

</style>
