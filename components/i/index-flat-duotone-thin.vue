<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u2mvrstlq"/><path class="r7rhcrycy"/><path class="cllzgnvrr"/><path class="vfzgreb6n"/><path class="cj2tbzbzv"/><path class="y-vga5bbj"/><path class="uilxv67me"/><path class="isrkj8blm"/><path class="bvj__8b4y"/><path class="rrc90qj9p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:index-flat-duotone-thin" /></template>
<style>
.bvj__8b4y {
  d: path("M20 4v11");
}

.cj2tbzbzv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m18 13 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cllzgnvrr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 17h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.isrkj8blm {
  d: path("M3 17h13");
}

.r7rhcrycy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 11h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rrc90qj9p {
  d: path("m18 13 2 2 2 -2");
}

.u2mvrstlq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uilxv67me {
  d: path("M3 11h13");
}

.vfzgreb6n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 4v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y-vga5bbj {
  d: path("M3 5h13");
}

</style>
