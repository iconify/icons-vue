<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qecovn3xi"/><path class="ujw6lacqu"/><path class="n88kwi36z"/><path class="wxo2urbks"/><path class="f8r7v8e3i"/><path class="kn0tcm93r"/><path class="jg5k_rbda"/><path class="qp__wx2fk"/><path class="dhp6n31qa"/><path class="gjb6r-bki"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:git-merge-duotone-thin" /></template>
<style>
.dhp6n31qa {
  d: path("M6 7.5V12l4.5 4.5");
}

.f8r7v8e3i {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 7.5V12l-4.5 4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gjb6r-bki {
  d: path("M18 7.5V12l-4.5 4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jg5k_rbda {
  d: path("M16 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.kn0tcm93r {
  d: path("M4 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.n88kwi36z {
  fill: currentColor;
  d: path("M10 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.qecovn3xi {
  fill: currentColor;
  d: path("M4 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.qp__wx2fk {
  d: path("M10 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ujw6lacqu {
  fill: currentColor;
  d: path("M16 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wxo2urbks {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 7.5V12l4.5 4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
