<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wk7qv1b_m"/><path class="h8ap6qb-d"/><path class="uw5kuce7r"/><path class="qkig0y_8f"/><path class="sw6_egbdo"/><path class="fhbl5kbmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:align-horizontal-space-between-duotone-regular" /></template>
<style>
.fhbl5kbmk {
  d: path("M21 3v18");
}

.h8ap6qb-d {
  fill: currentColor;
  d: path("M14 7h4v10h-4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qkig0y_8f {
  d: path("M6 7h4v10H6Z");
}

.sw6_egbdo {
  d: path("M14 7h4v10h-4Z");
}

.uw5kuce7r {
  d: path("M3 3v18");
}

.wk7qv1b_m {
  fill: currentColor;
  d: path("M6 7h4v10H6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
