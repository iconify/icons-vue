<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pwu8_hbyi"/><path class="bsomdtb1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-horizontal-space-around-two-tone" /></template>
<style>
.bsomdtb1t {
  d: path("M20 2V22M4 2V22M9 9V15C9 16.11 9.9033 17 11 17H12H13C14.1125 17 15 16.105 15 15V9C15 7.896 14.1045 7 13 7H12H11C9.8954 7 9 7.901 9 9Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pwu8_hbyi {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 1C4.5523 1 5 1.448 5 2V22C5 22.552 4.5523 23 4 23C3.4477 23 3 22.552 3 22V2C3 1.448 3.4477 1 4 1ZM20 1C20.5523 1 21 1.448 21 2V22C21 22.552 20.5523 23 20 23C19.4477 23 19 22.552 19 22V2C19 1.448 19.4477 1 20 1ZM13 6C14.6569 6 16 7.344 16 9V15C16 16.655 14.6672 18 13 18H11C9.3555 18 8 16.667 8 15V9C8 7.351 9.3412 6 11 6H13Z");
  stroke: none;
}

</style>
