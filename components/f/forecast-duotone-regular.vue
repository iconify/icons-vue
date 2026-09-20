<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="nyxb76bqx"/><path class="p4sziubhp"/><path class="ucabifahv"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="y09n-7bbz"/><path class="xjxf-fbjv"/><path class="z0_yphh3l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:forecast-duotone-regular" /></template>
<style>
.iulb4mb6k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nyxb76bqx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m6 16 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.p4sziubhp {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m13 9 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pd-i35blz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

.ucabifahv {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m17 5 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xjxf-fbjv {
  d: path("m13 9 2 -2");
}

.y09n-7bbz {
  d: path("m6 16 5 -5");
}

.z0_yphh3l {
  d: path("m17 5 2 -2");
}

</style>
