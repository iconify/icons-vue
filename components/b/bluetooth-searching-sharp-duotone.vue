<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="rsjuddc2b"/><path class="ezb26abmt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bluetooth-searching-sharp-duotone" /></template>
<style>
.ezb26abmt {
  d: path("M20.9033 7.4L21.1652 8C21.7158 9.2617 22 10.6234 22 12C22 13.3766 21.7158 14.7383 21.1652 16L20.9033 16.6M3.0967 7.4L2.8348 8C2.2842 9.2617 2 10.6234 2 12C2 13.3766 2.2842 14.7383 2.8348 16L3.0967 16.6");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rsjuddc2b {
  stroke-opacity: 0.4;
  d: path("M6.7071 6.7071L17 17L12 22L12 2L17 7L6.7071 17.2929");
}

</style>
