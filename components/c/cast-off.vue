<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="q5koslwkz"/><path class="jtmnk0bjy"/><path class="c0954yb2f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cast-off" /></template>
<style>
.c0954yb2f {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3.25 19.5h.01");
}

.jtmnk0bjy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12.25a7.5 7.5 0 0 1 7.5 7.5m-7.5-3.5a3.5 3.5 0 0 1 3.5 3.5");
}

.q5koslwkz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8V6.75a2.5 2.5 0 0 1 2.5-2.5h13.5a2.5 2.5 0 0 1 2.5 2.5v10.5a2.5 2.5 0 0 1-2.5 2.5h-5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
