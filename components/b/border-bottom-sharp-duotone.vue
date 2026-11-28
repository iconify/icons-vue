<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="sccmezy6s"/><path class="wbie4eb1v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:border-bottom-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sccmezy6s {
  stroke-opacity: 0.4;
  d: path("M3 7L3 3L7 3M9.5 3L14.5 3M17 3L21 3L21 7M21 9.5L21 14.5M3 14.5L3 9.5");
}

.wbie4eb1v {
  d: path("M21 17L21 21L3 21L3 17");
}

</style>
