<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i7z0vob4i"/><path class="mbt4yzbhr"/><path class="wy1_19byi"/><path class="gkgr58b-d"/><path class="tv7sb1bck"/><path class="xf07dvr8m"/><path class="z9ittvbis"/><path class="bxa1b1bso"/><path class="x7g1r9bby"/><path class="fr472ib_x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:long-polling-duotone-regular" /></template>
<style>
.bxa1b1bso {
  d: path("M6 5v14");
}

.fr472ib_x {
  d: path("m13 16 3 3 3 -3");
}

.gkgr58b-d {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i7z0vob4i {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 5h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mbt4yzbhr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tv7sb1bck {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m13 16 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wy1_19byi {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x7g1r9bby {
  d: path("M16 5v14");
}

.xf07dvr8m {
  d: path("M2 5h20");
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
