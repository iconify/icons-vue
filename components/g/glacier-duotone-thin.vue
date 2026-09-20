<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jwhpx6uzp"/><path class="ncqgqabut"/><path class="nmrrrlaph"/><path class="zrcrjuw2y"/><path class="g6e5e7bhp"/><path class="p4c11pbyi"/><path class="ng7_l5bbi"/><path class="qgimpuszh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:glacier-duotone-thin" /></template>
<style>
.g6e5e7bhp {
  d: path("m2 8 6 6 6 -6 6 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jwhpx6uzp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m2 8 6 6 6 -6 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ncqgqabut {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m2 15 6 6 6 -6 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ng7_l5bbi {
  d: path("m6 4 4 4");
}

.nmrrrlaph {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p4c11pbyi {
  d: path("m2 15 6 6 6 -6 6 6");
}

.qgimpuszh {
  d: path("m14 4 4 4");
}

.zrcrjuw2y {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
