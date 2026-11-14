<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x1ryrk17e"/><path class="m241-3zhq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:entrance-zone" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m241-3zhq {
  d: path("m11 9l3 3l-3 3");
}

.x1ryrk17e {
  d: path("M2.5 6.5v-2a2 2 0 0 1 2-2h2m11 0h2a2 2 0 0 1 2 2v2m0 11v2a2 2 0 0 1-2 2h-2m-11 0h-2a2 2 0 0 1-2-2v-2m8-15h3m-3 19h3m-11-11v3m19-3v3M14 7h2a1.5 1.5 0 0 1 1.5 1.5v7A1.5 1.5 0 0 1 16 17h-2m-7.5-5H14");
}

</style>
