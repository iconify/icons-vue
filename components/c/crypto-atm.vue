<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="nnj6rtlkc"/><path class="aqtrz7bqu"/><path class="j-hrxqe-r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crypto-atm" /></template>
<style>
.aqtrz7bqu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 6.75h10.5M7.75 10h8.5v9.75a1.5 1.5 0 0 1-1.5 1.5h-5.5a1.5 1.5 0 0 1-1.5-1.5Z");
}

.j-hrxqe-r {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 15.5h.01");
}

.nnj6rtlkc {
  width: 18.5px;
  height: 10px;
  x: 2.75px;
  y: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
