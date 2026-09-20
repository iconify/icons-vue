<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dom865bkj"/><path class="xoaby-lkq"/><path class="v6op74bzs"/><path class="n93ox5byq"/><path class="mrpfkeaiv"/><path class="juvl5cc7r"/><path class="t-euypbap"/><path class="kpspt_bpo"/><path class="yo-0d--rc"/><path class="jnysnpbhj"/><path class="uto0n9pso"/><path class="fs--blxyx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:key-pair-duotone-thin" /></template>
<style>
.dom865bkj {
  fill: currentColor;
  d: path("M3 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fs--blxyx {
  d: path("M9 13v3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jnysnpbhj {
  d: path("M17 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.juvl5cc7r {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 13v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kpspt_bpo {
  d: path("M7 8h10");
}

.mrpfkeaiv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 16h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n93ox5byq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 8v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t-euypbap {
  d: path("M3 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.uto0n9pso {
  d: path("M7 16h10");
}

.v6op74bzs {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 8h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xoaby-lkq {
  fill: currentColor;
  d: path("M17 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.yo-0d--rc {
  d: path("M15 8v3");
}

</style>
