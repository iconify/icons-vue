<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="atm68wq7c"/><path class="ugq6qwb4p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-vertical-distribute-end-sharp-two-tone" /></template>
<style>
.atm68wq7c {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 13C16.552 13 17 13.448 17 14V19H23V21H1V19H7V14C7 13.448 7.448 13 8 13H16ZM20 3C20.552 3 21 3.448 21 4V9H23V11H1V9H3V4C3 3.448 3.448 3 4 3H20Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ugq6qwb4p {
  d: path("M23 20H1M23 10H1M16 14V20H8V14H16ZM20 10H4V4H20V10Z");
}

</style>
