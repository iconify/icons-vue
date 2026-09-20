<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g6btd475d"/><path class="bkuclybie"/><path class="rencte-ct"/><path class="nvbmjob4n"/><path class="iwfr4ca5f"/><path class="mn-a1zb6m"/><path class="s25-orfog"/><path class="tdux9oy4s"/><path class="xh38rmboq"/><path class="n9q35emrt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dependency-map-duotone-regular" /></template>
<style>
.bkuclybie {
  fill: currentColor;
  d: path("M17 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.g6btd475d {
  fill: currentColor;
  d: path("M3 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.iwfr4ca5f {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m17.5 10.5 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mn-a1zb6m {
  d: path("M3 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.n9q35emrt {
  d: path("m17.5 10.5 -4 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nvbmjob4n {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m6.5 10.5 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rencte-ct {
  fill: currentColor;
  d: path("M10 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s25-orfog {
  d: path("M17 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.tdux9oy4s {
  d: path("M10 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.xh38rmboq {
  d: path("m6.5 10.5 4 4");
}

</style>
