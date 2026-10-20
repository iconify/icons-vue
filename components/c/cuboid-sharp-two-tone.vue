<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="mxivlactl"/><path class="jccrl8b-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cuboid-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jccrl8b-s {
  d: path("M3 8L8 3L21 3L21 16L16 21L3 21ZM3 8L16 8L16 21M16 8L21 3");
}

.mxivlactl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2.2929 7.2929L7.2929 2.2929C7.4804 2.1054 7.7348 2 8 2L21 2C21.5523 2 22 2.4477 22 3L22 16C22 16.2652 21.8946 16.5196 21.7071 16.7071L16.7071 21.7071C16.5196 21.8946 16.2652 22 16 22L3 22C2.4477 22 2 21.5523 2 21L2 8C2 7.7348 2.1054 7.4804 2.2929 7.2929Z");
  stroke: none;
}

</style>
