<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="leg5z9b9q"/><path class="oviggobsx"/><path class="hsbaytb4s"/><path class="ybyc8pxiv"/><path class="kkm03rbxe"/><path class="gdxs68qsm"/><path class="utps5obsq"/><path class="axphtybjp"/><path class="r1wy_ibgj"/><path class="bos0j4biy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:coral-reef-duotone-bold" /></template>
<style>
.axphtybjp {
  d: path("M15 21V9l-3 -3");
}

.bos0j4biy {
  d: path("M3 21h18");
}

.gdxs68qsm {
  d: path("M7 21v-9L4 9");
}

.hsbaytb4s {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 21V9l-3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kkm03rbxe {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 21h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.leg5z9b9q {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 21v-9L4 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oviggobsx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m7 15 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r1wy_ibgj {
  d: path("m15 13 4 -4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.utps5obsq {
  d: path("m7 15 4 -4");
}

.ybyc8pxiv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 13 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
