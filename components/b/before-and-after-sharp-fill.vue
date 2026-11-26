<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="flfh2307c"/><path class="up5oa8bpl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:before-and-after-sharp-fill" /></template>
<style>
.flfh2307c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 4L22 4C22.5523 4 23 4.4477 23 5L23 19C23 19.5523 22.5523 20 22 20L13 20L13 22.0001L13 23.0001L11 23.0001L11 22.0001L11 19L11 12L11 4.9922L11 2.0001L11 1.0001L13 1.0001L13 2.0001Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.up5oa8bpl {
  d: path("M9 19L8 19L2 19L2 5L8 5L9 5");
}

</style>
