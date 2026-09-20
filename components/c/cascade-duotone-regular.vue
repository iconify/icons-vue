<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b2b6babct"/><path class="pp--out0p"/><path class="ojb_ipbvm"/><path class="l5p5yybyx"/><path class="enu8lyb0i"/><path class="ewmg6nb_g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cascade-duotone-regular" /></template>
<style>
.b2b6babct {
  fill: currentColor;
  d: path("M5 2.5 7.5 5 5 7.5 2.5 5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.enu8lyb0i {
  d: path("m12 9.5 2.5 2.5 -2.5 2.5L9.5 12Z");
}

.ewmg6nb_g {
  d: path("m19 16.5 2.5 2.5 -2.5 2.5 -2.5 -2.5Z");
}

.l5p5yybyx {
  d: path("M5 2.5 7.5 5 5 7.5 2.5 5Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ojb_ipbvm {
  fill: currentColor;
  d: path("m19 16.5 2.5 2.5 -2.5 2.5 -2.5 -2.5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.pp--out0p {
  fill: currentColor;
  d: path("m12 9.5 2.5 2.5 -2.5 2.5L9.5 12Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
