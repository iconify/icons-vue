<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="sywtpcb7r"/><rect class="sdel59bth"/><path class="ymq9xqbfy"/><path class="m4k5yjb6l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:engine" /></template>
<style>
.m4k5yjb6l {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 14h.01M12 14h.01M15 14h.01");
}

.sdel59bth {
  width: 7.5px;
  height: 2.75px;
  x: 8.25px;
  y: 4.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.sywtpcb7r {
  width: 12.5px;
  height: 9.25px;
  x: 5.75px;
  y: 9.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ymq9xqbfy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75v1.5M2.75 11v5.5m0-2.75h3M21.25 11v5.5m-3-2.75h3");
}

</style>
