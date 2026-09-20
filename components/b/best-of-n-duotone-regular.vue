<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xnjd2sbjx"/><path class="g8ge0y5fo"/><path class="ub6op3wbj"/><path class="ke3ma707p"/><path class="dhm9wy0nm"/><path class="o8scmcc3i"/><path class="uxy9sxbfx"/><path class="o50_pabww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:best-of-n-duotone-regular" /></template>
<style>
.dhm9wy0nm {
  d: path("M3 5h10");
}

.g8ge0y5fo {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ke3ma707p {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 12 2 2 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o50_pabww {
  d: path("m16 12 2 2 4 -4");
}

.o8scmcc3i {
  d: path("M3 12h10");
}

.ub6op3wbj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 19h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uxy9sxbfx {
  d: path("M3 19h10");
}

.xnjd2sbjx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 5h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
