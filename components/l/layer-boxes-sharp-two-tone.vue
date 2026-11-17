<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="nesncm_fi"/><path class="em6ww58bo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layer-boxes-sharp-two-tone" /></template>
<style>
.em6ww58bo {
  d: path("M2 12L12 17.5L22 12M2 12V16.5L12 22L22 16.5V12M22 12V7.5L12 2L2 7.5V12M2 7.5L12 13L22 7.5");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nesncm_fi {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.634 1.069C11.908 0.961 12.219 0.98 12.481 1.124L22.481 6.624C22.801 6.8 23 7.135 23 7.5V16.5C23 16.865 22.801 17.2 22.481 17.376L12.481 22.876C12.182 23.041 11.818 23.041 11.519 22.876L1.519 17.376C1.199 17.2 1 16.865 1 16.5V7.5C1 7.135 1.199 6.8 1.519 6.624L11.519 1.124L11.634 1.069Z");
  stroke: none;
}

</style>
