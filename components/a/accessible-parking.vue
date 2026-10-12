<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="dt3j7ib_c"/><path class="xrm_jibas"/><path class="qjp3fzk3v"/><path class="hbgu0xbsk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:accessible-parking" /></template>
<style>
.dt3j7ib_c {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.hbgu0xbsk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.25 10v3h2.25l.75 2.25M14.4 11.5a2.6 2.6 0 1 0 3.1 4");
}

.qjp3fzk3v {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.25 7.5h.01");
}

.xrm_jibas {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 17V7h3a3 3 0 0 1 0 6h-3");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
