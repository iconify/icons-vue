<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m8c8atiya"/><path class="axxhvjb7u"/><path class="uv_37sb-u"/><path class="bmz4u0b2r"/><path class="n0n63pb2v"/><path class="u8l45l7zq"/><path class="gr97ezb6h"/><path class="we3axlb2u"/><path class="c8z9pcctp"/><path class="g2k78ab8a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:graph-memory-duotone-thin" /></template>
<style>
.axxhvjb7u {
  fill: currentColor;
  d: path("M6.5 5.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.bmz4u0b2r {
  fill: currentColor;
  d: path("M11 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.c8z9pcctp {
  d: path("M8.5 6.5 11 9");
}

.g2k78ab8a {
  d: path("M15.5 6.5 13 9");
}

.gr97ezb6h {
  d: path("M15.5 5.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m8c8atiya {
  fill: currentColor;
  d: path("M4 15v4h16v-4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.n0n63pb2v {
  d: path("M4 15v4h16v-4");
}

.u8l45l7zq {
  d: path("M6.5 5.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.uv_37sb-u {
  fill: currentColor;
  d: path("M15.5 5.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.we3axlb2u {
  d: path("M11 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
