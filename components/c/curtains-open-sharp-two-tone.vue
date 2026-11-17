<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="xml9ofb1g"/><path class="c8c0oib8g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:curtains-open-sharp-two-tone" /></template>
<style>
.c8c0oib8g {
  d: path("M2 3H22M4 3V21H8C8 18.5 6 16.5 4 15C7.5 12.5 10 9 10 3M20 3V21H16C16 18.5 18 16.5 20 15C16.5 12.5 14 9 14 3");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xml9ofb1g {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 4H21V21C21 21.552 20.552 22 20 22H16C15.448 22 15 21.552 15 21C15 18.473 16.666 16.478 18.378 15.016C16.972 13.859 15.74 12.487 14.811 10.793C13.782 8.917 13.15 6.69 13.024 4H10.976C10.85 6.69 10.218 8.917 9.189 10.793C8.26 12.487 7.028 13.859 5.621 15.016C7.334 16.479 9 18.473 9 21C9 21.552 8.552 22 8 22H4C3.448 22 3 21.552 3 21V4H2V2H22V4Z");
  stroke: none;
}

</style>
