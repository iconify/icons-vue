<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="y1y8owb2o"/><path class="yr59vwb5i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clipboard-off-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y1y8owb2o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 21V22C21 22.5523 20.552 23 20 23H4C3.448 23 3 22.5523 3 22V4C3 3.7239 3.112 3.4739 3.293 3.2929L21 21ZM6 2.3431V2C6 1.4477 6.448 1 7 1H17C17.552 1 18 1.4477 18 2V3H20C20.552 3 21 3.4477 21 4V17.3431L6 2.3431Z");
  stroke: none;
}

.yr59vwb5i {
  d: path("M4 4V22H20V20M1.707 1.7071L22.293 22.2929");
}

</style>
