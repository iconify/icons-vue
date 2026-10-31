<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="shdi9bpks"/><path class="aft2t_mhq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ev-charger-sharp-fill" /></template>
<style>
.aft2t_mhq {
  d: path("M14 17L20 17L20 10M22 6L22 3M18 6L18 3");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.shdi9bpks {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14 23L2 23C1.4477 23 1 22.5523 1 22L1 2C1 1.4477 1.4477 1 2 1L14 1C14.5523 1 15 1.4477 15 2L15 21L23 21L23 23L14 23ZM10.1 8.2L8.5 7L5.2 11.4C5.0702 11.5731 5 11.7836 5 12C5 12.5523 5.4477 13 6 13L8 13L5.9 15.8L7.5 17L10.8 12.6C10.9298 12.4269 11 12.2164 11 12C11 11.4477 10.5523 11 10 11L8 11L10.1 8.2ZM18 5L22 5C22.5523 5 23 5.4477 23 6L23 10C23 10.5523 22.5523 11 22 11L18 11C17.4477 11 17 10.5523 17 10L17 6C17 5.4477 17.4477 5 18 5Z");
  stroke: none;
}

</style>
