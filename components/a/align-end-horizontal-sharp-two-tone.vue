<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="v4-jm9b7q"/><path class="wyhcfffdv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-end-horizontal-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v4-jm9b7q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 23H1V21H23V23ZM10 1C10.552 1 11 1.448 11 2V18C11 18.552 10.552 19 10 19H4C3.448 19 3 18.552 3 18V2C3 1.448 3.448 1 4 1H10ZM20 9C20.552 9 21 9.448 21 10V18C21 18.552 20.552 19 20 19H14C13.448 19 13 18.552 13 18V10C13 9.448 13.448 9 14 9H20Z");
  stroke: none;
}

.wyhcfffdv {
  d: path("M23 22H1M20 18H14V10H20V18ZM10 18H4V2H10V18Z");
}

</style>
