<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zxrob3sge"/><path class="cpc3z_b1u"/><path class="hhx45xbgc"/><path class="m63bznb8z"/><path class="dfcdzc65k"/><path class="z5135gcut"/><path class="o7mqvuj4j"/><path class="kdmnrabtq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:end-to-end-duotone-bold" /></template>
<style>
.cpc3z_b1u {
  fill: currentColor;
  d: path("M17 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.dfcdzc65k {
  d: path("M3 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hhx45xbgc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8 8 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kdmnrabtq {
  d: path("M17 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.m63bznb8z {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 12.5V15h-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o7mqvuj4j {
  d: path("M15 12.5V15h-2.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.z5135gcut {
  d: path("m8 8 4 4");
}

.zxrob3sge {
  fill: currentColor;
  d: path("M3 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
