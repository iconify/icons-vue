<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l6cp2-b8s"/><path class="k_2z93bzc"/><path class="jcknv4b7x"/><path class="ycxs_nhrn"/><path class="u20-axb8k"/><path class="a7vpafiwa"/><path class="n3p0zmbop"/><path class="zwn7edcbm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:for-each-duotone-thin" /></template>
<style>
.a7vpafiwa {
  d: path("M6 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jcknv4b7x {
  fill: currentColor;
  d: path("M16 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.k_2z93bzc {
  fill: currentColor;
  d: path("M11 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.l6cp2-b8s {
  fill: currentColor;
  d: path("M6 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.n3p0zmbop {
  d: path("M11 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.u20-axb8k {
  d: path("M15.8 3.84a9 9 0 1 1 -7.6 0");
}

.ycxs_nhrn {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15.8 3.84a9 9 0 1 1 -7.6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zwn7edcbm {
  d: path("M16 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
