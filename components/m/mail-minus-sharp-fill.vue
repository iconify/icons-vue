<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="hrwa_z-6s"/><path class="voy745bbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mail-minus-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hrwa_z-6s {
  fill: currentColor;
  d: path("M5 4L19 4C20.6569 4 22 5.3431 22 7L12.7071 11C12.2846 11.2817 11.7154 11.2817 11.2929 11L2 7C2 5.3431 3.3432 4 5 4Z");
  stroke: none;
}

.voy745bbr {
  d: path("M13 20L2 20L2 4L22 4L22 11M2 7L11.2929 11C11.7154 11.2817 12.2846 11.2817 12.7071 11L22 7M15 17L23 17");
}

</style>
