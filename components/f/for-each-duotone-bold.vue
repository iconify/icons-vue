<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="l6cp2-b8s"/><path class="k_2z93bzc"/><path class="jcknv4b7x"/><path class="jhqgucbgb"/><path class="u20-axb8k"/><path class="a7vpafiwa"/><path class="n3p0zmbop"/><path class="zwn7edcbm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:for-each-duotone-bold" /></template>
<style>
.a7vpafiwa {
  d: path("M6 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.jcknv4b7x {
  fill: currentColor;
  d: path("M16 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jhqgucbgb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15.8 3.84a9 9 0 1 1 -7.6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
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

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u20-axb8k {
  d: path("M15.8 3.84a9 9 0 1 1 -7.6 0");
}

.zwn7edcbm {
  d: path("M16 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
