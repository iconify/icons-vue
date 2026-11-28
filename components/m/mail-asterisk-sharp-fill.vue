<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="s6vpnyndj"/><path class="cg1p92bzr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mail-asterisk-sharp-fill" /></template>
<style>
.cg1p92bzr {
  d: path("M13 20H2V4H22V11M2 7L11.293 11C11.715 11.282 12.285 11.282 12.707 11L22 7M19 13.5V20.5M16.2 19.1L21.8 14.9M16.2 14.9L21.8 19.1");
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
