<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lyk3lbb0z"/><path class="ksh4iaclj"/><path class="h0xx2obvc"/><path class="zpl29uvhf"/><path class="voz_x46if"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:elt-outline-regular" /></template>
<style>
.h0xx2obvc {
  d: path("M13 12h3");
}

.ksh4iaclj {
  d: path("M2 5a5 2.5 0 0 0 10 0");
}

.lyk3lbb0z {
  d: path("M2 5a5 2.5 0 0 1 10 0v8a5 2.5 0 0 1 -10 0Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.voz_x46if {
  d: path("M15 17a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

.zpl29uvhf {
  d: path("m16 9 3 3 -3 3");
}

</style>
