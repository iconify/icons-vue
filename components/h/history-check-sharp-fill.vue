<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="l433_2h6a"/><path class="h12u_mbag"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:history-check-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.h12u_mbag {
  d: path("M2.32 2.79L6.543 4L5.339 8.22");
}

.l433_2h6a {
  d: path("M13 22H12C6.477 22 2 17.52 2 12C2 8.96 3.358 6.23 5.5 4.4C5.662 4.26 5.828 4.13 5.999 4M22 13V12C22 6.48 17.523 2 12 2C11.662 2 11.329 2.02 11 2.05L10.099 2.14M12 5V12H18M15.707 18.71L18 21L22.293 16.71");
}

</style>
