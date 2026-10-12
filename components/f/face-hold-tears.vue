<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="c6vt1lbds"/><path class="ru0hrxb7l"/><path class="goa6xmsjx"/><path class="op_g3bc5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:face-hold-tears" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.goa6xmsjx {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 10.25h.01m5.99 0h.01");
}

.op_g3bc5k {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 12.25c.9.6 2.1.6 3 0m3 0c.9.6 2.1.6 3 0m-7.25 4c.9.6 1.75.9 2.75.9s1.85-.3 2.75-.9");
}

.ru0hrxb7l {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.25 8l2.5-1m7 1l-2.5-1");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
