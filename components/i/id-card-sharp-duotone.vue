<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="b2ps5cbvw"/><path class="rg-8-mj5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:id-card-sharp-duotone" /></template>
<style>
.b2ps5cbvw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3L22 3C22.5523 3 23 3.4477 23 4L23 20C23 20.5523 22.5523 21 22 21L2 21C1.4477 21 1 20.5523 1 20L1 4C1 3.4477 1.4477 3 2 3Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rg-8-mj5j {
  d: path("M11 10C11 11.1046 10.1046 12 9 12C7.8954 12 7 11.1046 7 10C7 8.8954 7.8954 8 9 8C10.1046 8 11 8.8954 11 10ZM5 21L5 20C5 17.7909 6.7909 16 9 16C11.2091 16 13 17.7909 13 20L13 21M14 10L19 10M14 14L19 14");
}

</style>
