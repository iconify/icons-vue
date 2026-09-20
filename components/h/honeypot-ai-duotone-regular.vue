<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z1ra8bb5p"/><path class="eeop0ibex"/><path class="ce7y3gbnp"/><path class="b4kvax4jt"/><path class="b3s4djbny"/><path class="u7m7z6ojw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:honeypot-ai-duotone-regular" /></template>
<style>
.b3s4djbny {
  d: path("M4 5h16");
}

.b4kvax4jt {
  d: path("M5 8v12h14V8");
}

.ce7y3gbnp {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 5h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.eeop0ibex {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 8v12h14V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u7m7z6ojw {
  d: path("M10 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.z1ra8bb5p {
  fill: currentColor;
  d: path("M10 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
