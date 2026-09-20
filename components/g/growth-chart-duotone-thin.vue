<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e5rxwxb6q"/><path class="hlbks9ztk"/><path class="nsda17r0u"/><path class="qe97cg-lx"/><path class="dqeovmbtl"/><path class="fua3x2iyd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:growth-chart-duotone-thin" /></template>
<style>
.dqeovmbtl {
  d: path("m5 18 4 -4 3 3 7 -7");
}

.e5rxwxb6q {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 3v18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fua3x2iyd {
  d: path("M17 6h4");
}

.hlbks9ztk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m5 18 4 -4 3 3 7 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nsda17r0u {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 6h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qe97cg-lx {
  d: path("M3 3v18h18");
}

</style>
