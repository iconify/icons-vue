<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="nngulhfpg"/><ellipse class="duwevwymc"/><ellipse class="ke9ojpbos"/><path class="zhte3uxim"/><path class="jza2yfbtq"/><g class="ehej3-bmx"><path class="gf90lpbsq"/><path class="i62to1vdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:grimacing-face" /></template>
<style>
.duwevwymc {
  cx: 43.95px;
  cy: 56.46px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  rx: 7.92px;
  ry: 9.63px;
}

.ehej3-bmx {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.gf90lpbsq {
  d: path("M47.44 75.17h3.12v25h-3.12zm-15 0h3.12v25h-3.12zm60.01 0h3.12v25h-3.12zm-15.01 0h3.12v25h-3.12zm-15 0h3.12v25h-3.12z");
}

.i62to1vdl {
  d: path("M20.49 86.04h87.01v3.12H20.49z");
}

.jza2yfbtq {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M95 77.6c5.51 0 10 4.49 10 10s-4.49 10-10 10H33c-5.51 0-10-4.49-10-10s4.49-10 10-10zm0-4H33c-7.7 0-14 6.3-14 14s6.3 14 14 14h62c7.7 0 14-6.3 14-14s-6.3-14-14-14");
}

.ke9ojpbos {
  cx: 84.03px;
  cy: 56.46px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  rx: 7.92px;
  ry: 9.63px;
}

.nngulhfpg {
  fill: var(--svg-color--fcc21b, #fcc21b);
  d: path("M64 12.81C1.88 12.81.41 82.46.41 96.25c0 13.77 28.47 24.94 63.59 24.94s63.59-11.17 63.59-24.94c0-13.79-1.46-83.44-63.59-83.44");
}

.zhte3uxim {
  fill: var(--svg-color--fff, #fff);
  d: path("M95 101.6H33c-7.7 0-14-6.3-14-14s6.3-14 14-14h62c7.7 0 14 6.3 14 14s-6.3 14-14 14");
}

</style>
