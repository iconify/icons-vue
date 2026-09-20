<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="chyxoccgw"/><path class="icjnx2bvb"/><path class="jl-a685iy"/><path class="di0j27ojs"/><path class="hqu8-q-5e"/><path class="mwf5pf3ps"/><path class="vn2a6xb1r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:badminton-duotone-regular" /></template>
<style>
.chyxoccgw {
  fill: currentColor;
  d: path("M12 20c-3 0 -5 -2 -5 -4h10c0 2 -2 4 -5 4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.di0j27ojs {
  d: path("M17 16c2 -4 3 -9 4 -13");
}

.hqu8-q-5e {
  d: path("M3 3h18");
}

.icjnx2bvb {
  d: path("M12 20c-3 0 -5 -2 -5 -4h10c0 2 -2 4 -5 4");
}

.jl-a685iy {
  d: path("M7 16C5 12 4 7 3 3");
}

.mwf5pf3ps {
  d: path("M9 4v11");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vn2a6xb1r {
  d: path("M15 4v11");
}

</style>
