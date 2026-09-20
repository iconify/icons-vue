<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ci8aik1lf"/><path class="p-b7dhbbl"/><path class="tbmul1b-b"/><path class="gv3gpab3b"/><path class="ndk47rb8x"/><path class="wuvisubmw"/><path class="em798y7rn"/><path class="mi_m6achy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:archery-duotone-thin" /></template>
<style>
.ci8aik1lf {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 3c6 3 6 15 0 18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.em798y7rn {
  d: path("M6 12h14");
}

.gv3gpab3b {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m17 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mi_m6achy {
  d: path("m17 9 3 3 -3 3");
}

.ndk47rb8x {
  d: path("M8 3c6 3 6 15 0 18");
}

.p-b7dhbbl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tbmul1b-b {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 12h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wuvisubmw {
  d: path("M8 3v18");
}

</style>
