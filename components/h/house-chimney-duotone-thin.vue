<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="neg3b7q9q"/><path class="y0p2uub0j"/><path class="x1vcnpbhq"/><path class="rs3qt4avn"/><path class="qq2o6m5os"/><path class="cx8rytfxu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:house-chimney-duotone-thin" /></template>
<style>
.cx8rytfxu {
  d: path("M13 8h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.neg3b7q9q {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m2 21 7 -7 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qq2o6m5os {
  d: path("M13 14V5h6v16");
}

.rs3qt4avn {
  d: path("m2 21 7 -7 7 7");
}

.x1vcnpbhq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 8h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y0p2uub0j {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 14V5h6v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
