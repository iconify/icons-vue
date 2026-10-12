<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="rzw4fhumv"/><path class="sewyf1xoj"/><path class="du0p_jb0p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crescent-star-eid" /></template>
<style>
.du0p_jb0p {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 4.5h.01");
}

.rzw4fhumv {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.88 4.01a8.5 8.5 0 1 0 7.42 11.87a7 7 0 1 1-7.42-11.87");
}

.sewyf1xoj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.14 9.07l.55 1.22q.14.32.49.36l1.33.14q.34.03.08.27l-.99.89q-.26.24-.19.58l.28 1.3q.07.35-.23.17l-1.16-.67q-.3-.17-.6 0l-1.16.67q-.3.18-.23-.17l.28-1.3q.07-.34-.19-.58l-.99-.89q-.26-.24.08-.27l1.33-.14q.35-.04.49-.36l.55-1.22q.14-.32.28 0");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
