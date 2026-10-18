<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="pvnngvmrf"/><path class="c2pbmbb6m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hexagon-sharp-two-tone" /></template>
<style>
.c2pbmbb6m {
  d: path("M12 2L21 6.8809L21 17.1191L12 22L3 17.1191L3 6.8809L12 2Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pvnngvmrf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12.4767 1.1209L21.4767 6.0018C21.7992 6.1767 22 6.514 22 6.8809L22 17.1191C22 17.486 21.7992 17.8233 21.4767 17.9982L12.4767 22.8791C12.3304 22.9584 12.1665 23 12 23C11.8335 23 11.6696 22.9584 11.5233 22.8791L2.5233 17.9982C2.2008 17.8233 2 17.486 2 17.1191L2 6.8809C2 6.514 2.2008 6.1767 2.5233 6.0018L11.5233 1.1209C11.6696 1.0416 11.8335 1 12 1C12.1665 1 12.3304 1.0416 12.4767 1.1209Z");
  stroke: none;
}

</style>
