<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="l87c2qtcr"/><path class="xq-fdrb6l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flow-document-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.l87c2qtcr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 4L22 4C22.5523 4 23 4.4477 23 5L23 17C23 17.5523 22.5523 18 22 18C21.7432 18 21.4963 17.9012 21.3103 17.7241C20.1482 16.6173 18.6048 16 17 16C15.3952 16 13.8518 16.6173 12.6897 17.7241C11.1556 19.1851 9.1184 20 7 20C4.8816 20 2.8444 19.1851 1.3103 17.7241C1.1122 17.5354 1 17.2737 1 17L1 5C1 4.4477 1.4477 4 2 4Z");
  stroke: none;
}

.xq-fdrb6l {
  d: path("M2 17L2 5L22 5L22 17C20.6519 15.7161 18.8616 15 17 15C15.1384 15 13.3481 15.7161 12 17C10.6519 18.2839 8.8616 19 7 19C5.1384 19 3.3481 18.2839 2 17Z");
}

</style>
