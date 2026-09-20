<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b8cis0btm"/><path class="xlgmapbrd"/><path class="vqal-abhe"/><path class="bpdfs5b6a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:health-probe-duotone-regular" /></template>
<style>
.b8cis0btm {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 8h4.5l2 -2 4 4 2 -2H21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bpdfs5b6a {
  d: path("m9 15 2 2 4 -4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vqal-abhe {
  d: path("M3 8h4.5l2 -2 4 4 2 -2H21");
}

.xlgmapbrd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 15 2 2 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
