<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="lo_lt5b5d"/><circle class="wcwdkbbur"/><path class="h3qkj9bop"/><path class="fpk68_bsl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dj-deck" /></template>
<style>
.fpk68_bsl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.5 7.5v6l-2.25 2.25");
}

.h3qkj9bop {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 12h.01");
}

.lo_lt5b5d {
  width: 18.5px;
  height: 14.5px;
  x: 2.75px;
  y: 4.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.wcwdkbbur {
  cx: 10px;
  cy: 12px;
  r: 4.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
