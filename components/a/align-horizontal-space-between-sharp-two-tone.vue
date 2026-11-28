<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="g3meqhb4j"/><path class="gp6eonbgg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-horizontal-space-between-sharp-two-tone" /></template>
<style>
.g3meqhb4j {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 6H9C9.5523 6 10 6.4477 10 7V17C10 17.5523 9.5523 18 9 18H5V23H3V1H5ZM19 6H15C14.4477 6 14 6.4477 14 7V17C14 17.5523 14.4477 18 15 18H19V23H21V1H19Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.gp6eonbgg {
  d: path("M20 1V23M4 1V23M4 7V17H9V7H4ZM15 7V17H20V7H15Z");
}

</style>
