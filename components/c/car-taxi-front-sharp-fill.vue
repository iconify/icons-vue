<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="e1uxq_beq"/><path class="txdd2jbuq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:car-taxi-front-sharp-fill" /></template>
<style>
.e1uxq_beq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.0011 5L18 5C18.5026 5 18.9271 5.373 18.9917 5.8714L19.6294 10.7904L19.6924 11L21 11C21.5523 11 22 11.4477 22 12L22 20C22 20.5523 21.5523 21 21 21L20 21L20 22C20 22.5523 19.5523 23 19 23L18 23C17.4477 23 17 22.5523 17 22L17 21L7 21L7 22C7 22.5523 6.5523 23 6 23L5 23C4.4477 23 4 22.5523 4 22L4 21L3 21C2.4477 21 2 20.5523 2 20L2 12C2 11.4477 2.4477 11 3 11L4.3076 11L4.3706 10.7904L5.0083 5.8714C5.0729 5.373 5.4974 5 6 5L7.9989 5L9.5936 1.5776C9.7578 1.2253 10.1113 1 10.5 1L13.5 1C13.8887 1 14.2422 1.2253 14.4064 1.5776L16.0011 5ZM6.3601 11L17.6398 11L17.1213 7L6.8787 7L6.3601 11ZM6 15L6 17L9 17L9 15L6 15ZM15 15L15 17L18 17L18 15L15 15Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.txdd2jbuq {
  d: path("M5.35177 11L2.5 11M18.6482 11L21.5 11");
}

</style>
