<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jh5lbnbtr"/><path class="t20035b-s"/><path clip-rule="evenodd" class="kew2exbfm"/><path class="km1gx1e-p"/><path clip-rule="evenodd" class="rhqa9bc-e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cast-alert-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jh5lbnbtr {
  stroke-opacity: 0.4;
  d: path("M2 9V4H13M22 13V20H13");
}

.kew2exbfm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 20C3 20.552 2.552 21 2 21C1.448 21 1 20.552 1 20C1 19.448 1.448 19 2 19C2.552 19 3 19.448 3 20Z");
  stroke: none;
}

.km1gx1e-p {
  d: path("M19 3V7");
}

.rhqa9bc-e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 10C20 10.552 19.552 11 19 11C18.448 11 18 10.552 18 10C18 9.448 18.448 9 19 9C19.552 9 20 9.448 20 10Z");
  stroke: none;
}

.t20035b-s {
  d: path("M1 16H2C4.209 16 6 17.791 6 20V21M1 12H2C6.418 12 10 15.582 10 20V21");
}

</style>
