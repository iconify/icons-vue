<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="n2k2ocy2p"/><path class="gt97uebns"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fire-truck-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.gt97uebns {
  d: path("M5 18L4 18L2 18L2 10L16 10M1 6L2 6L12 6L12 10M4 6L4 10M8 6L8 10M9 18L10 18L14 18L15 18M22 12L16 12L16 6L19 6L22 11L22 18L20 18L19 18M17.5 6L17.5 4L17.5 3M9 18C9 19.1046 8.1046 20 7 20C5.8954 20 5 19.1046 5 18C5 16.8954 5.8954 16 7 16C8.1046 16 9 16.8954 9 18ZM19 18C19 19.1046 18.1046 20 17 20C15.8954 20 15 19.1046 15 18C15 16.8954 15.8954 16 17 16C18.1046 16 19 16.8954 19 18Z");
}

.n2k2ocy2p {
  fill: currentColor;
  d: path("M15 18L9 18C9 16.8954 8.1046 16 7 16C5.8954 16 5 16.8954 5 18L2 18L2 10L15.5 10L15.5 12C15.5 12.2761 15.7239 12.5 16 12.5L19 12.5L22 12.5L22 18.0001L19 18C19 16.8954 18.1046 16 17 16C15.8954 16 15 16.8954 15 18Z");
  stroke: none;
}

</style>
