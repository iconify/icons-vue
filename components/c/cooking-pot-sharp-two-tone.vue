<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="qkxvgg08u"/><path class="lh6-4eb0u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cooking-pot-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lh6-4eb0u {
  d: path("M4 11L4 21L20 21L20 11M1 11L23 11M3 7L21 7M8 7L8 3L16 3L16 7");
}

.qkxvgg08u {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M3 11C3 10.4477 3.4477 10 4 10L20 10C20.5523 10 21 10.4477 21 11L21 21C21 21.5523 20.5523 22 20 22L4 22C3.4477 22 3 21.5523 3 21L3 11ZM7 7L7 3C7 2.4477 7.4477 2 8 2L16 2C16.5523 2 17 2.4477 17 3L17 7C17 7.5523 16.5523 8 16 8L8 8C7.4477 8 7 7.5523 7 7Z");
  stroke: none;
}

</style>
