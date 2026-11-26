<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="cu75339rk"/><path class="xgevoeb2g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flow-manual-operation-sharp-two-tone" /></template>
<style>
.cu75339rk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 4L21.9999 4C22.5522 4 22.9999 4.4477 22.9999 5C22.9999 5.0929 22.987 5.1854 22.9614 5.2747L18.9615 19.2747C18.8389 19.704 18.4465 20 18 20L6 20C5.5535 20 5.1611 19.704 5.0385 19.2747L1.0386 5.2747C1.013 5.1854 1.0001 5.0929 1.0001 5C1.0001 4.4477 1.4478 4 2.0001 4Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xgevoeb2g {
  d: path("M2.0001 5L21.9999 5L18 19L6 19Z");
}

</style>
