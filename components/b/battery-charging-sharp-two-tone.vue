<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="uvg86u3ox"/><path class="t-rww2btg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:battery-charging-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t-rww2btg {
  d: path("M22 8.5L22 15.5M11.3 7.6L8 12L12 12L8.7 16.4");
}

.uvg86u3ox {
  stroke-opacity: 0.4;
  d: path("M7 6L2 6L2 18L6.5 18M13.5 6L18 6L18 18L13 18");
}

</style>
