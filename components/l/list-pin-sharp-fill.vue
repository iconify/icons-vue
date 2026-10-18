<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="u1ztvq2yr"/><path class="cpi9euf-i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-pin-sharp-fill" /></template>
<style>
.cpi9euf-i {
  d: path("M15.5 15L15.5 21M1 10L8 10M1 15L6 15M1 20L12 20");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u1ztvq2yr {
  fill: currentColor;
  d: path("M11.5 3L19.5 3C20.0523 3 20.5 3.4477 20.5 4L20.5 7C20.5 7.5523 20.0523 8 19.5 8L18.5 8L18.5 9.9648L22.5547 12.6679C22.8329 12.8534 23 13.1656 23 13.5L23 15C23 15.5523 22.5523 16 22 16L9 16C8.4477 16 8 15.5523 8 15L8 13.5C8 13.1656 8.1671 12.8534 8.4453 12.6679L12.5 9.9648L12.5 8L11.5 8C10.9477 8 10.5 7.5523 10.5 7L10.5 4C10.5 3.4477 10.9477 3 11.5 3Z");
  stroke: none;
}

</style>
