<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="g5ncw42dh"/><path class="q5hmxc_qj"/><path class="iyreedmkv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-off-sharp-two-tone" /></template>
<style>
.g5ncw42dh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 23H4C3.4477 23 3 22.5523 3 22V3L21 21V22C21 22.5523 20.5523 23 20 23H16Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.iyreedmkv {
  d: path("M4 4V22H20V20M1.7071 1.7071L22.2929 22.2929");
}

.q5hmxc_qj {
  stroke-opacity: 0.4;
  d: path("M20 15.34V8L14 2H6.5M14 2V8H20");
}

</style>
