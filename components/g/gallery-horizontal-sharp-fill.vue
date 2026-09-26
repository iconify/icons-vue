<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="o9ukiybod"/><path class="r8svpwbcv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gallery-horizontal-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o9ukiybod {
  fill: currentColor;
  d: path("M7 2L17 2C17.5523 2 18 2.4477 18 3L18 21C18 21.5523 17.5523 22 17 22L7 22C6.4477 22 6 21.5523 6 21L6 3C6 2.4477 6.4477 2 7 2Z");
  stroke: none;
}

.r8svpwbcv {
  d: path("M3 2L3 22M21 2L21 22");
}

</style>
