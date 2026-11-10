<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="bufi47b8f"/><path class="jgkto5v5i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-start-vertical-sharp-two-tone" /></template>
<style>
.bufi47b8f {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 23H1V1H3V23ZM22 13C22.552 13 23 13.448 23 14V20C23 20.552 22.552 21 22 21H6C5.448 21 5 20.552 5 20V14C5 13.448 5.448 13 6 13H22ZM14 3C14.552 3 15 3.448 15 4V10C15 10.552 14.552 11 14 11H6C5.448 11 5 10.552 5 10V4C5 3.448 5.448 3 6 3H14Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jgkto5v5i {
  d: path("M2 1V23M6 4V10H14V4H6ZM6 14V20H22V14H6Z");
}

</style>
