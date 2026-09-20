<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tbr--mb3k"/><path class="wz2u9fjma"/><path class="fjjtwtbze"/><path class="s6ftf884l"/><path class="pjcnnqbic"/><path class="u52vfsbff"/><path class="xedmbxbzm"/><path class="jkqgno60a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:human-loop-duotone-bold" /></template>
<style>
.fjjtwtbze {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 4h3v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jkqgno60a {
  d: path("M8.5 17a3.5 3.5 0 0 1 7 0");
}

.pjcnnqbic {
  d: path("M16 5.07a8 8 0 1 1 -8 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s6ftf884l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8.5 17a3.5 3.5 0 0 1 7 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tbr--mb3k {
  fill: currentColor;
  d: path("M10 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.u52vfsbff {
  d: path("M5 4h3v3");
}

.wz2u9fjma {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 5.07a8 8 0 1 1 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xedmbxbzm {
  d: path("M10 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
