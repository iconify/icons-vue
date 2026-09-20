<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="uu1a3h43e"/><path class="f3r6jjb4a"/><path class="v2xyhybzi"/><path class="c-vnm8iux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:edge-duotone-bold" /></template>
<style>
.c-vnm8iux {
  d: path("M15 12h3");
}

.f3r6jjb4a {
  d: path("M20 3v18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uu1a3h43e {
  fill: currentColor;
  d: path("M5.5 12a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.v2xyhybzi {
  d: path("M5.5 12a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

</style>
