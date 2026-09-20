<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tzzszcbro"/><path class="d4v3t3bns"/><path class="duxy6wbvl"/><path class="ok9ioqb8x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:groundedness-duotone-bold" /></template>
<style>
.d4v3t3bns {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 17h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.duxy6wbvl {
  d: path("m7 9 4 4 6 -6");
}

.ok9ioqb8x {
  d: path("M4 17h16");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tzzszcbro {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m7 9 4 4 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
