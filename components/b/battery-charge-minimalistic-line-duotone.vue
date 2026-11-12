<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="m4dmr2b-x"/><path class="tnfby2q5d"/><path class="pu97ujszu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:battery-charge-minimalistic-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m4dmr2b-x {
  d: path("M10 20H11.5C15.2712 20 17.1569 20 18.3284 18.8284C19.5 17.6569 19.5 15.7712 19.5 12C19.5 8.22876 19.5 6.34315 18.3284 5.17157C17.1569 4 15.2712 4 11.5 4H10C6.22876 4 4.34315 4 3.17157 5.17157C2 6.34315 2 8.22876 2 12C2 15.7712 2 17.6569 3.17157 18.8284C4.34315 20 6.22876 20 10 20Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.pu97ujszu {
  stroke-linejoin: round;
  d: path("M11.5 9L9 12H12.5L10 15");
}

.tnfby2q5d {
  d: path("M22 14L22 10");
}

</style>
