<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f_hy4hbgg"/><path class="j033x8blp"/><path class="jyqbe3amu"/><path class="vzxh37pxv"/><path class="zugrvnb7t"/><path class="t-oxscctn"/><path class="j08f9ezai"/><path class="dihddo_by"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:horizon-duotone-thin" /></template>
<style>
.dihddo_by {
  d: path("M6 18h12");
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

.j033x8blp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m5 13 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j08f9ezai {
  d: path("m12 13 4 -4 4 4");
}

.jyqbe3amu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 13 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t-oxscctn {
  d: path("m5 13 4 -4 4 4");
}

.vzxh37pxv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 18h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zugrvnb7t {
  d: path("M2 13h20");
}

</style>
