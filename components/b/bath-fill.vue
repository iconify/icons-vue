<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dis6srbis"/><path class="shp7s3tyu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bath-fill" /></template>
<style>
.dis6srbis {
  fill: currentColor;
  d: path("M2.988 10.0001C2.992 10 2.996 10 3 10L21 10C21.004 10 21.008 10 21.012 10.0001L22 10.0001C22.5523 10.0001 23 10.4478 23 11.0001C23 11.5524 22.5523 12.0001 22 12.0001L22 15C22 17.7614 19.7614 20 17 20L7 20C4.2386 20 2 17.7614 2 15L2 12.0001C1.4477 12.0001 1 11.5523 1 11.0001C1 10.4478 1.4477 10.0001 2 10.0001L2.988 10.0001Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.shp7s3tyu {
  d: path("M3 11L3 6C3 4.3431 4.3431 3 6 3C7.0463 3 8.0169 3.5451 8.5615 4.4384M7.5 5.5L10 3M8 19L7 21M16 19L17 21");
}

</style>
