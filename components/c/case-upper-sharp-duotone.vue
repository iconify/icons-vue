<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="trtifv9xg"/><path class="k2m0qnbly"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:case-upper-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.k2m0qnbly {
  d: path("M15.941 18.67L18.998 10L22.055 18.67M16.882 16H21.114");
}

.trtifv9xg {
  stroke-opacity: 0.4;
  d: path("M1.93 18.63L7.002 6L12.074 18.63M4.19 13H9.813");
}

</style>
