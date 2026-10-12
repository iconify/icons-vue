<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="an0-utdrw"/><path class="k_ah1izyg"/><path class="qu0bxjbhg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:authenticator" /></template>
<style>
.an0-utdrw {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 4.5px;
}

.k_ah1izyg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.92 5.88l2.41.99q.92.38.92 1.38v1.06q0 1-.73 1.68l-2.79 2.58q-.73.68-1.46 0l-2.79-2.58q-.73-.68-.73-1.68V8.25q0-1 .92-1.38l2.41-.99q.92-.38 1.84 0");
}

.qu0bxjbhg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 17.25h.01m3.99 0h.01m3.99 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
