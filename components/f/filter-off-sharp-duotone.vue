<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="xy9uzxb_m"/><path class="qib3ujb7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:filter-off-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qib3ujb7r {
  d: path("M1.707 1.707L22.293 22.293");
}

.xy9uzxb_m {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 15.12V19C15 19.379 14.786 19.725 14.447 19.895L13 20.618L10.447 21.894C9.782 22.227 9 21.743 9 21V14.657H11L13 16.657V13.12L15 15.12ZM5.657 2H21C21.845 2 22.309 2.983 21.772 3.636L15.233 11.576L5.657 2Z");
  stroke: none;
}

</style>
