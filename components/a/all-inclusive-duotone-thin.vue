<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xawcw5elo"/><path class="rsu8hn7ln"/><path class="dcpzcnwjc"/><path class="bv1y61bvs"/><path class="ils7yp4cg"/><path class="v2r_pnsln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:all-inclusive-duotone-thin" /></template>
<style>
.bv1y61bvs {
  d: path("M4 16a8 8 0 0 1 16 0");
}

.dcpzcnwjc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 9 3 3 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ils7yp4cg {
  d: path("M2 16h20");
}

.rsu8hn7ln {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 16h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v2r_pnsln {
  d: path("m8 9 3 3 5 -5");
}

.xawcw5elo {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 16a8 8 0 0 1 16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
