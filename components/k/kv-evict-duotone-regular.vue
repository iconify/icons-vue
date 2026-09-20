<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ozusmjceo"/><path class="wimmg3bgi"/><path class="bpqmg-bcl"/><path class="hz4hy96ag"/><path class="vlvmdnbxo"/><path class="ab69i60qd"/><path class="q4hnnr4zu"/><path class="ly2b2eaue"/><path class="lgk47ib7d"/><path class="gorvssbqo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:kv-evict-duotone-regular" /></template>
<style>
.ab69i60qd {
  d: path("M5.5 4H3v16h2.5");
}

.bpqmg-bcl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5.5 4H3v16h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gorvssbqo {
  d: path("M17.5 9.5 20 12l-2.5 2.5");
}

.hz4hy96ag {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14.5 12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lgk47ib7d {
  d: path("M14.5 12h3");
}

.ly2b2eaue {
  d: path("M8.5 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ozusmjceo {
  fill: currentColor;
  d: path("M8.5 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.q4hnnr4zu {
  d: path("M8.5 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.vlvmdnbxo {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17.5 9.5 20 12l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wimmg3bgi {
  fill: currentColor;
  d: path("M8.5 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
