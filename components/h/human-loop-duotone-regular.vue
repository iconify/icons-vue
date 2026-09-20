<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tbr--mb3k"/><path class="a8m--3b4n"/><path class="zq9m2db-h"/><path class="qfzdtlb1b"/><path class="pjcnnqbic"/><path class="u52vfsbff"/><path class="xedmbxbzm"/><path class="jkqgno60a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:human-loop-duotone-regular" /></template>
<style>
.a8m--3b4n {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 5.07a8 8 0 1 1 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jkqgno60a {
  d: path("M8.5 17a3.5 3.5 0 0 1 7 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pjcnnqbic {
  d: path("M16 5.07a8 8 0 1 1 -8 0");
}

.qfzdtlb1b {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8.5 17a3.5 3.5 0 0 1 7 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tbr--mb3k {
  fill: currentColor;
  d: path("M10 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.u52vfsbff {
  d: path("M5 4h3v3");
}

.xedmbxbzm {
  d: path("M10 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.zq9m2db-h {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 4h3v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
