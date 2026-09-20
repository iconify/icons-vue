<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ik_7mybce"/><path class="l8d0kxbma"/><path class="gln57mb0o"/><path class="u-kmlrghs"/><path class="vi4joi7cm"/><path class="sxlwlmkmh"/><path class="x67_elb1a"/><path class="wj95cacbv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bin-full-duotone-regular" /></template>
<style>
.gln57mb0o {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 12v8h12v-8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ik_7mybce {
  fill: currentColor;
  d: path("M8 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.l8d0kxbma {
  fill: currentColor;
  d: path("M13 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sxlwlmkmh {
  d: path("M4 12h16");
}

.u-kmlrghs {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 12h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vi4joi7cm {
  d: path("M6 12v8h12v-8");
}

.wj95cacbv {
  d: path("M13 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.x67_elb1a {
  d: path("M8 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
