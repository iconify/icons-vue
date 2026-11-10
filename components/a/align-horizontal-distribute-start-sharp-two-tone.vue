<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ku887vb-u"/><path class="f09ska_9n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-horizontal-distribute-start-sharp-two-tone" /></template>
<style>
.f09ska_9n {
  d: path("M4 1V23M14 1V23M20 8H14V16H20V8ZM4 4V20H10V4H4Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ku887vb-u {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 3H10C10.552 3 11 3.448 11 4V20C11 20.552 10.552 21 10 21H5V23H3V1H5V3ZM15 7H20C20.552 7 21 7.448 21 8V16C21 16.552 20.552 17 20 17H15V23H13V1H15V7Z");
  stroke: none;
}

</style>
