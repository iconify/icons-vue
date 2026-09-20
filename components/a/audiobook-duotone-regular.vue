<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b6-9mc2ec"/><path class="jg7wewb9v"/><path class="lhanhxbya"/><path class="fse74oemj"/><path class="ocopvj5ps"/><path class="ic00xab8f"/><path class="cb9u5zbqi"/><path class="xyckaabnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:audiobook-duotone-regular" /></template>
<style>
.b6-9mc2ec {
  fill: currentColor;
  d: path("M6 10a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.cb9u5zbqi {
  d: path("M2 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.fse74oemj {
  d: path("M6 10a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

.ic00xab8f {
  d: path("M4 12a8 8 0 0 1 16 0");
}

.jg7wewb9v {
  fill: currentColor;
  d: path("M2 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.lhanhxbya {
  fill: currentColor;
  d: path("M18 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

.ocopvj5ps {
  d: path("M9 8v13");
}

.xyckaabnm {
  d: path("M18 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
