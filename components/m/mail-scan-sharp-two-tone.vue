<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="o8uyy455h"/><path class="b_i2z1b8l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mail-scan-sharp-two-tone" /></template>
<style>
.b_i2z1b8l {
  d: path("M3 13V3H21V13M3 6L11.36361 8.84948C11.74386 9.05015 12.25614 9.05015 12.63639 8.84948L21 6M1 13H23M2 17H11M22 17H13M21 21H17M15 21H9M7 21H3");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o8uyy455h {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 14H3C2.4477 14 2 13.5523 2 13V3C2 2.4477 2.4477 2 3 2H21C21.5523 2 22 2.4477 22 3V13C22 13.5523 21.5523 14 21 14Z");
  stroke: none;
}

</style>
