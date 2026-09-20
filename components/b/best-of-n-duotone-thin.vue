<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bw0_0vbfj"/><path class="fz6tc-4je"/><path class="qcb83wbuk"/><path class="p925lhbvr"/><path class="dhm9wy0nm"/><path class="o8scmcc3i"/><path class="uxy9sxbfx"/><path class="o50_pabww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:best-of-n-duotone-thin" /></template>
<style>
.bw0_0vbfj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dhm9wy0nm {
  d: path("M3 5h10");
}

.fz6tc-4je {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o50_pabww {
  d: path("m16 12 2 2 4 -4");
}

.o8scmcc3i {
  d: path("M3 12h10");
}

.p925lhbvr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 12 2 2 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qcb83wbuk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 19h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uxy9sxbfx {
  d: path("M3 19h10");
}

</style>
