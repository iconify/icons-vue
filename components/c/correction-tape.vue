<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="kei-_rbsj"/><path class="qxyd16gsh"/><path class="h3qkj9bop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:correction-tape" /></template>
<style>
.h3qkj9bop {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 12h.01");
}

.kei-_rbsj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 4.5H13q1.5 0 2.14 1.35l1.22 2.55q.64 1.35 2.12 1.61l1.29.23q1.48.26 1.48 1.76t-1.48 1.76l-1.29.23q-1.48.26-2.12 1.61l-1.22 2.55Q14.5 19.5 13 19.5H4.5Q3 19.5 3 18V6q0-1.5 1.5-1.5");
}

.qxyd16gsh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 8.5a3.5 3.5 0 1 1 0 7a3.5 3.5 0 1 1 0-7");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
