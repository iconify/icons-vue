<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nams8ab0e"/><path class="s-9609b2o"/><path class="j-uhg7vsc"/><path class="m44kqpqtt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:braces-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j-uhg7vsc {
  d: path("M11 3H8v7l-2 2 2 2v7h3");
}

.m44kqpqtt {
  d: path("M13 3h3v7l2 2 -2 2v7h-3");
}

.nams8ab0e {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 3H8v7l-2 2 2 2v7h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s-9609b2o {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 3h3v7l2 2 -2 2v7h-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
