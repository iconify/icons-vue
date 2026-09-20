<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hsvpncbrw"/><path class="y9xhft0uq"/><path class="okqpn0bmf"/><path class="ihsx9nb3v"/><path class="mupo5fbhr"/><path class="ehib3abci"/><path class="fhs8z1bjw"/><path class="fduloacov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:exam-hall-duotone-regular" /></template>
<style>
.ehib3abci {
  d: path("M15 8h6v4h-6Z");
}

.fduloacov {
  d: path("M15 16h6v4h-6Z");
}

.fhs8z1bjw {
  d: path("M3 16h6v4H3Z");
}

.hsvpncbrw {
  fill: currentColor;
  d: path("M3 8h6v4H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ihsx9nb3v {
  fill: currentColor;
  d: path("M15 16h6v4h-6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mupo5fbhr {
  d: path("M3 8h6v4H3Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.okqpn0bmf {
  fill: currentColor;
  d: path("M3 16h6v4H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.y9xhft0uq {
  fill: currentColor;
  d: path("M15 8h6v4h-6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
