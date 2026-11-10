<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="u2t173b6t"/><path class="d9mevqfwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-end-vertical-sharp-two-tone" /></template>
<style>
.d9mevqfwj {
  d: path("M22 1V23M18 4V10H10V4H18ZM18 14V20H2V14H18Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u2t173b6t {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 23H21V1H23V23ZM18 13C18.552 13 19 13.448 19 14V20C19 20.552 18.552 21 18 21H2C1.448 21 1 20.552 1 20V14C1 13.448 1.448 13 2 13H18ZM18 3C18.552 3 19 3.448 19 4V10C19 10.552 18.552 11 18 11H10C9.448 11 9 10.552 9 10V4C9 3.448 9.448 3 10 3H18Z");
  stroke: none;
}

</style>
