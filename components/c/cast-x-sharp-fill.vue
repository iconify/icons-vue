<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ek3_l5bzh"/><path clip-rule="evenodd" class="kew2exbfm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cast-x-sharp-fill" /></template>
<style>
.ek3_l5bzh {
  d: path("M2 9V4H13M22 13V20H13M1 16H2C4.209 16 6 17.791 6 20V21M1 12H2C6.418 12 10 15.582 10 20V21M15.707 3.707L22.293 10.293M22.293 3.707L15.707 10.293");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kew2exbfm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 20C3 20.552 2.552 21 2 21C1.448 21 1 20.552 1 20C1 19.448 1.448 19 2 19C2.552 19 3 19.448 3 20Z");
  stroke: none;
}

</style>
