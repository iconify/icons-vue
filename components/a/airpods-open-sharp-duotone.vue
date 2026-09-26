<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="n2lht5b1f"/><path class="jyrpkpb6l"/><path class="rj2y4vkzd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:airpods-open-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jyrpkpb6l {
  d: path("M1 9L23 9M8 9L8 10L16 10L16 9");
}

.n2lht5b1f {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M1 21L1 9C1 8.4477 1.4477 8 2 8L2 3C2 2.4477 2.4477 2 3 2L21 2C21.5523 2 22 2.4477 22 3L22 8C22.5523 8 23 8.4477 23 9L23 21C23 21.5523 22.5523 22 22 22L2 22C1.4477 22 1 21.5523 1 21Z");
  stroke: none;
}

.rj2y4vkzd {
  fill: currentColor;
  d: path("M13 14C13 14.5523 12.5523 15 12 15C11.4477 15 11 14.5523 11 14C11 13.4477 11.4477 13 12 13C12.5523 13 13 13.4477 13 14Z");
  stroke: none;
}

</style>
