<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x1xh4_byw"/><path class="y6-gchbkp"/><path class="iklp5dbqm"/><path class="hppiisbif"/><path class="tqteed1fm"/><path class="hqkel0bnd"/><path class="uaurn5bqf"/><path class="oqfv9rb9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:canyon-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hppiisbif {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 21h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hqkel0bnd {
  d: path("M22 3h-6v18");
}

.iklp5dbqm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 17 2 -2 2 2 2 -2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oqfv9rb9x {
  d: path("M2 21h20");
}

.tqteed1fm {
  d: path("M2 3h6v18");
}

.uaurn5bqf {
  d: path("m8 17 2 -2 2 2 2 -2 2 2");
}

.x1xh4_byw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 3h6v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y6-gchbkp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M22 3h-6v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
