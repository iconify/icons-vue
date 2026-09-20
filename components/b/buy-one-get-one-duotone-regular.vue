<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vq4q60_me"/><path class="gwiwsnv1o"/><path class="rstn0-buy"/><path class="vo1-lv2pt"/><path class="oz3eccbug"/><path class="rza2khwwm"/><path class="v1-or777z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:buy-one-get-one-duotone-regular" /></template>
<style>
.gwiwsnv1o {
  fill: currentColor;
  d: path("M7 13h3.5v4H7Z");
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

.oz3eccbug {
  d: path("M7 8a5 5 0 0 1 10 0");
}

.rstn0-buy {
  fill: currentColor;
  d: path("M13.5 13H17v4h-3.5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rza2khwwm {
  d: path("M7 13h3.5v4H7Z");
}

.v1-or777z {
  d: path("M13.5 13H17v4h-3.5Z");
}

.vo1-lv2pt {
  d: path("M3 10a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.vq4q60_me {
  fill: currentColor;
  d: path("M3 10a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
