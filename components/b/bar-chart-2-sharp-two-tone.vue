<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="c4p3adbxf"/><path class="n8f3dyh2u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bar-chart-2-sharp-two-tone" /></template>
<style>
.c4p3adbxf {
  stroke-opacity: 0.4;
  d: path("M12 8L12 23M20 1L20 23");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.n8f3dyh2u {
  d: path("M4 15L4 23");
}

</style>
