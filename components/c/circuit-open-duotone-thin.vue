<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ylas06exf"/><path class="gob4qybps"/><path class="mqdq6sbba"/><path class="xudngvbpe"/><path class="eez_fubsi"/><path class="c4e1y7wvc"/><path class="h36909btm"/><path class="rzbbkyb0w"/><path class="a76nyxbck"/><path class="i7lk_63qj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:circuit-open-duotone-thin" /></template>
<style>
.a76nyxbck {
  d: path("M18 14v5");
}

.c4e1y7wvc {
  d: path("M4 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.eez_fubsi {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 12 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gob4qybps {
  fill: currentColor;
  d: path("M16 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.h36909btm {
  d: path("M16 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i7lk_63qj {
  d: path("m8 12 6 -6");
}

.mqdq6sbba {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 5v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rzbbkyb0w {
  d: path("M6 5v5");
}

.xudngvbpe {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 14v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ylas06exf {
  fill: currentColor;
  d: path("M4 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
