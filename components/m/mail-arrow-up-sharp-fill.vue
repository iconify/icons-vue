<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="s6vpnyndj"/><path class="dnh27-bzr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mail-arrow-up-sharp-fill" /></template>
<style>
.dnh27-bzr {
  d: path("M13 20H2V7M2 7V4H22V7M2 7L11.293 11C11.715 11.282 12.285 11.282 12.707 11L22 7M22 7V11M19 21V14M22.293 17.293L19 14L15.707 17.293");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s6vpnyndj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 4H19C20.657 4 22 5.343 22 7L12.707 11C12.285 11.282 11.715 11.282 11.293 11L2 7C2 5.343 3.343 4 5 4Z");
  stroke: none;
}

</style>
