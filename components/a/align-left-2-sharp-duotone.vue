<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="f-qcku-wb"/><path class="y9s618baa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-left-2-sharp-duotone" /></template>
<style>
.f-qcku-wb {
  stroke-opacity: 0.4;
  d: path("M7 4.5L22 4.5M7 9.5L22 9.5M7 14.5L19 14.5M7 19.5L15 19.5");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y9s618baa {
  d: path("M3 2L3 22");
}

</style>
