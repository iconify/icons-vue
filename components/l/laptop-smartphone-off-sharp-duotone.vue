<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="e5nt67tzt"/><path class="jnxhkmbek"/><path class="qib3ujb7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:laptop-smartphone-off-sharp-duotone" /></template>
<style>
.e5nt67tzt {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22.233 22.353L21.586 23H13C12.448 23 12 22.552 12 22V12.12L22.233 22.353ZM12.702 9.045C12.796 9.016 12.896 9 13 9H22C22.552 9 23 9.448 23 10V19.343L12.702 9.045Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jnxhkmbek {
  stroke-opacity: 0.4;
  d: path("M4 14V4M6.657 2H7.657H20V5M10 18H2V14H10");
}

.qib3ujb7r {
  d: path("M1.707 1.707L22.293 22.293");
}

</style>
