<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fbee_g1qa"/><path class="p7seggbwz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:code-sharp-duotone" /></template>
<style>
.fbee_g1qa {
  stroke-opacity: 0.4;
  d: path("M8.2993 4.6508L2 12L8.2993 19.3492");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p7seggbwz {
  d: path("M15.7007 4.6508L22 12L15.7007 19.3492");
}

</style>
