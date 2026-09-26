<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="n6x0dbbwd"/><path class="da91uxbtb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:code-xml-sharp-two-tone" /></template>
<style>
.da91uxbtb {
  d: path("M9.7928 19.7253L14.2072 4.2747");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.n6x0dbbwd {
  stroke-opacity: 0.4;
  d: path("M6.3002 6.6247L2 12L6.3002 17.3753M17.6998 6.6247L22 12L17.6998 17.3753");
}

</style>
