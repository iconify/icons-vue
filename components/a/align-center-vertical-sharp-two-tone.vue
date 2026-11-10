<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lsghc7bud"/><path class="mg174dbeg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-center-vertical-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lsghc7bud {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 3H16C16.552 3 17 3.448 17 4V10C17 10.552 16.552 11 16 11H13V13H20C20.552 13 21 13.448 21 14V20C21 20.552 20.552 21 20 21H13V23H11V21H4C3.448 21 3 20.552 3 20V14C3 13.448 3.448 13 4 13H11V11H8C7.448 11 7 10.552 7 10V4C7 3.448 7.448 3 8 3H11V1H13V3Z");
  stroke: none;
}

.mg174dbeg {
  d: path("M12 1V4M12 10V14M12 20V23M16 4V10H8V4H16ZM20 14V20H4V14H20Z");
}

</style>
