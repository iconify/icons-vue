<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rzbhhg_xy"/><path class="nyy274nxr"/><path class="l65u3r18p"/><path class="dr0g4gb1n"/><path class="j1f41eokg"/><path class="atoje4bsc"/><path class="njj_4bcir"/><path class="xj193cz1p"/><path class="e948j-b5x"/><path class="pmuiqo95v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:balcony-duotone-thin" /></template>
<style>
.atoje4bsc {
  d: path("M2 6h20");
}

.dr0g4gb1n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 6v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e948j-b5x {
  d: path("M18 6v11");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j1f41eokg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 17h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l65u3r18p {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 6v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.njj_4bcir {
  d: path("M6 6v11");
}

.nyy274nxr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 6v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pmuiqo95v {
  d: path("M2 17h20");
}

.rzbhhg_xy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 6h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xj193cz1p {
  d: path("M12 6v11");
}

</style>
