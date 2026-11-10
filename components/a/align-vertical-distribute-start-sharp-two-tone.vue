<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="t67h1kb5m"/><path class="noyp0pb1o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-vertical-distribute-start-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.noyp0pb1o {
  d: path("M23 4H1M23 14H1M16 10V4H8V10H16ZM20 14H4V20H20V14Z");
}

.t67h1kb5m {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 15H21V20C21 20.552 20.552 21 20 21H4C3.448 21 3 20.552 3 20V15H1V13H23V15ZM23 5H17V10C17 10.552 16.552 11 16 11H8C7.448 11 7 10.552 7 10V5H1V3H23V5Z");
  stroke: none;
}

</style>
