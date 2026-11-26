<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="asar4e5ud"/><path class="bhkfnn56v"/><path clip-rule="evenodd" class="s8cqp6bir"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:atm-sharp-duotone" /></template>
<style>
.asar4e5ud {
  stroke-opacity: 0.4;
  d: path("M6 4L2 4L2 10L6 10M18 4L22 4L22 10L18 10");
}

.bhkfnn56v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 12C15 13.6569 13.6569 15 12 15C10.3431 15 9 13.6569 9 12C9 10.3431 10.3431 9 12 9C13.6569 9 15 10.3431 15 12ZM13 12C13 11.4477 12.5523 11 12 11C11.4477 11 11 11.4477 11 12C11 12.5523 11.4477 13 12 13C12.5523 13 13 12.5523 13 12Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s8cqp6bir {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 12L19 20C19 20.5523 18.5523 21 18 21L6 21C5.4477 21 5 20.5523 5 20L5 4C5 3.4477 5.4477 3 6 3L18 3C18.5523 3 19 3.4477 19 4ZM15 12C15 10.3431 13.6569 9 12 9C10.3431 9 9 10.3431 9 12C9 13.6569 10.3431 15 12 15C13.6569 15 15 13.6569 15 12ZM13 12C13 12.5523 12.5523 13 12 13C11.4477 13 11 12.5523 11 12C11 11.4477 11.4477 11 12 11C12.5523 11 13 11.4477 13 12Z");
  stroke: none;
}

</style>
