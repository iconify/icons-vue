<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="okqi2lbic"/><path class="wh7ckkbxw"/><path class="b-pphqpeq"/><path class="sfnyx4wnk"/><path class="zbcez2bqg"/><path class="xscnsx3do"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:container-restart-duotone-regular" /></template>
<style>
.b-pphqpeq {
  d: path("M3 8a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.okqi2lbic {
  fill: currentColor;
  d: path("M3 8a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.sfnyx4wnk {
  d: path("M6 6v14");
}

.wh7ckkbxw {
  fill: currentColor;
  d: path("M11.5 9.5v6l3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xscnsx3do {
  d: path("M11.5 9.5v6l3 -3Z");
}

.zbcez2bqg {
  d: path("M9.5 9.5v6");
}

</style>
