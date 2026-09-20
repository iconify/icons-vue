<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b7uyqxwtl"/><path class="hosrnl1cs"/><path class="faypmibli"/><path class="ky4omnbla"/><path class="l0v-b4kbr"/><path class="az5esj3_g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:loan-repay-duotone-thin" /></template>
<style>
.az5esj3_g {
  d: path("M10.5 9.5 8 12l2.5 2.5");
}

.b7uyqxwtl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.faypmibli {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10.5 9.5 8 12l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hosrnl1cs {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ky4omnbla {
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
}

.l0v-b4kbr {
  d: path("M8 12h8");
}

</style>
