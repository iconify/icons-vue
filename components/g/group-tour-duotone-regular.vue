<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c7os3sb0q"/><path class="ad2jv3erj"/><path class="p0lbyib3y"/><path class="jzln5b9mk"/><path class="pmeincb2n"/><path class="q2fp4ccin"/><path class="hh49znbxn"/><path class="w-wacblka"/><path class="xz1gkzbgx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:group-tour-duotone-regular" /></template>
<style>
.ad2jv3erj {
  fill: currentColor;
  d: path("M9.5 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.c7os3sb0q {
  fill: currentColor;
  d: path("M4 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hh49znbxn {
  d: path("M3 19a4 4 0 0 1 8 0");
}

.jzln5b9mk {
  d: path("M4 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p0lbyib3y {
  fill: currentColor;
  d: path("M15 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.pmeincb2n {
  d: path("M9.5 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.q2fp4ccin {
  d: path("M15 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.w-wacblka {
  d: path("M8.5 19a4 4 0 0 1 8 0");
}

.xz1gkzbgx {
  d: path("M14 19a4 4 0 0 1 8 0");
}

</style>
