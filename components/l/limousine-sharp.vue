<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="hqbikf3sy"/><circle class="m_6c0ubwy"/><path class="bzy5_itsi"/><circle class="l991b5b6m"/><path class="s1f9ehlgm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:limousine-sharp" /></template>
<style>
.bzy5_itsi {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.75 19h.01");
}

.hqbikf3sy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.48 12.34l.79-.18L5 12l.43-.61l.89-1.28l.43-.61H17l.47.59l1.06 1.32l.47.59l.73.16l.79.18l.73.16v4.25H2.75V12.5zm1.02-.09h15.75m-12-2.75v2.75M11.5 9.5v2.75m3.25-2.75v2.75");
}

.l991b5b6m {
  cx: 18.25px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m_6c0ubwy {
  cx: 5.75px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s1f9ehlgm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.25 19h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
