<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e5rxwxb6q"/><path class="e1ccsd6cy"/><path class="qe97cg-lx"/><path class="yt1wgcb2d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:activation-duotone-thin" /></template>
<style>
.e1ccsd6cy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 17h7l7 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e5rxwxb6q {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 3v18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qe97cg-lx {
  d: path("M3 3v18h18");
}

.yt1wgcb2d {
  d: path("M5 17h7l7 -7");
}

</style>
