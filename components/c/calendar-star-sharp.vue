<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="tykp0sb6z"/><path class="i7l0ccctm"/><path class="pyj3lnjgg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:calendar-star-sharp" /></template>
<style>
.i7l0ccctm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 14h.01M8 17h.01");
}

.pyj3lnjgg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.39 13.82l.85 1.9l.14.32l.35.04l2.07.22l.35.03l-.26.24l-1.54 1.39l-.26.24l.07.34l.43 2.03l.07.35l-.3-.18l-1.81-1.04l-.3-.17l-.3.17l-1.81 1.04l-.3.18l.07-.35l.43-2.03l.07-.34l-.26-.24l-1.54-1.39l-.26-.24l.35-.03l2.07-.22l.35-.04l.14-.32l.85-1.9l.14-.32z");
}

.tykp0sb6z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 20.25h-7.5v-15h16.5v6M3.75 10h16.5M8 2.75v4.5m8-4.5v4.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
