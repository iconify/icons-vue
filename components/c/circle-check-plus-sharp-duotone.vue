<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ogehitbcm"/><path class="eq3a4chhw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-check-plus-sharp-duotone" /></template>
<style>
.eq3a4chhw {
  d: path("M19 15L19 23M15 19L23 19M7.7016 11.6644L10.6667 15L16.2984 8.6644");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ogehitbcm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 13L13 13L13 22C13 22.5523 12.5523 23 12 23C5.9249 23 1 18.0751 1 12C1 5.9249 5.9249 1 12 1C18.0751 1 23 5.9249 23 12C23 12.5523 22.5523 13 22 13Z");
  stroke: none;
}

</style>
