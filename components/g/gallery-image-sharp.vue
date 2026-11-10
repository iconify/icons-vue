<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="y_k5v3bbm"/><path clip-rule="evenodd" class="r6eciub7f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gallery-image-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r6eciub7f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15 11.5C15 12.33 14.328 13 13.5 13C12.672 13 12 12.33 12 11.5C12 10.67 12.672 10 13.5 10C14.328 10 15 10.67 15 11.5Z");
  stroke: none;
}

.y_k5v3bbm {
  d: path("M4 3H20M21 18.38L17 14.38L13 17.38L9 13.38L3 19.38M3 7H21V21H3V7Z");
}

</style>
