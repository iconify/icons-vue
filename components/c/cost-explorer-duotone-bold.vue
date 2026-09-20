<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="j5hk4ybky"/><path class="vyhobobtn"/><path class="h51gqww2n"/><path class="bm68p9f0y"/><path class="su9etdbad"/><path class="uidmmjb0u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cost-explorer-duotone-bold" /></template>
<style>
.bm68p9f0y {
  d: path("M6.5 10.5v3");
}

.h51gqww2n {
  d: path("M2 12a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

.j5hk4ybky {
  fill: currentColor;
  d: path("M2 12a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.su9etdbad {
  d: path("M14 10a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

.uidmmjb0u {
  d: path("m20 12.5 2 2");
}

.vyhobobtn {
  fill: currentColor;
  d: path("M14 10a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
