<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c4be54b1f"/><path class="ydpucsi6v"/><path class="bod4n0b3z"/><path class="ar9f68bct"/><path class="a5uqb5btg"/><path class="lzjw7bcdy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ecosystem-duotone-bold" /></template>
<style>
.a5uqb5btg {
  d: path("M9 14v4");
}

.ar9f68bct {
  d: path("M6 11a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.bod4n0b3z {
  d: path("M2 18h20");
}

.c4be54b1f {
  fill: currentColor;
  d: path("M6 11a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.lzjw7bcdy {
  d: path("M14 18v-5h4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ydpucsi6v {
  d: path("M2 18a10 10 0 0 1 20 0");
}

</style>
