<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="t55z6hp0m"/><path class="qib3ujb7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:credit-card-off-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qib3ujb7r {
  d: path("M1.707 1.707L22.293 22.293");
}

.t55z6hp0m {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.88 21H2C1.448 21 1 20.552 1 20V4C1 3.448 1.448 3 2 3H2.88L7.88 8H3V10H9.88L20.88 21ZM6.657 3H22C22.552 3 23 3.448 23 4V19.343L13.657 10H21V8H11.657L6.657 3Z");
  stroke: none;
}

</style>
