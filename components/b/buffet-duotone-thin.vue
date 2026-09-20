<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f_hy4hbgg"/><path class="ydkgc70eo"/><path class="x9_hi749k"/><path class="qh0h9bdva"/><path class="qz3by1b6e"/><path class="zugrvnb7t"/><path class="e325robmt"/><path class="bfcwd7bcm"/><path class="v7ifz5bvw"/><path class="leijmjbkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:buffet-duotone-thin" /></template>
<style>
.bfcwd7bcm {
  d: path("M13 13a4 4 0 0 1 8 0");
}

.e325robmt {
  d: path("M3 13a4 4 0 0 1 8 0");
}

.f_hy4hbgg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 13h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.leijmjbkg {
  d: path("M18 13v6");
}

.qh0h9bdva {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 13v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qz3by1b6e {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 13v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v7ifz5bvw {
  d: path("M6 13v6");
}

.x9_hi749k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 13a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ydkgc70eo {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 13a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zugrvnb7t {
  d: path("M2 13h20");
}

</style>
