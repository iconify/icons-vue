<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o48nut9qz"/><path class="r4indybxp"/><path class="ky48x0b1z"/><path class="zm8n9jbhc"/><path class="vbvr2ebxa"/><path class="uk0rveqaj"/><path class="xcm-54bzl"/><path class="a6m5kfb7k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bass-clef-duotone-regular" /></template>
<style>
.a6m5kfb7k {
  d: path("M18 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ky48x0b1z {
  fill: currentColor;
  d: path("M18 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

.o48nut9qz {
  fill: currentColor;
  d: path("M4 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.r4indybxp {
  fill: currentColor;
  d: path("M18 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.uk0rveqaj {
  d: path("M4 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.vbvr2ebxa {
  d: path("M7 6c4 0 8 2 8 6s-4 7 -8 8");
}

.xcm-54bzl {
  d: path("M18 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.zm8n9jbhc {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 6c4 0 8 2 8 6s-4 7 -8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
