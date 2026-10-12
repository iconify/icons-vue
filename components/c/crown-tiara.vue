<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="nhp6lzbpa"/><path class="a4sqm4byg"/><path class="ab9635v4b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crown-tiara" /></template>
<style>
.a4sqm4byg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 11h.01");
}

.ab9635v4b {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 20h17.5");
}

.nhp6lzbpa {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 16V8.5q0-1 .69-.27l2.87 3.04q.69.73 1.23-.11l3.42-5.32q.54-.84 1.08 0l3.42 5.32q.54.84 1.23.11l2.87-3.04q.69-.73.69.27V16q0 1-1 1H4.25q-1 0-1-1");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
