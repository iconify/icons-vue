<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wyj9kwb_b"/><path class="vefr08bem"/><path class="n7d250moc"/><path class="it83nbbll"/><path class="t4ju69b0v"/><path class="c_qwi1bzg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:at-least-once-duotone-thin" /></template>
<style>
.c_qwi1bzg {
  d: path("m14 14 2 2 3.5 -3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.it83nbbll {
  d: path("M5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.n7d250moc {
  d: path("M3 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.t4ju69b0v {
  d: path("m12 9 2 2 3.5 -3.5");
}

.vefr08bem {
  fill: currentColor;
  d: path("M5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wyj9kwb_b {
  fill: currentColor;
  d: path("M3 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
