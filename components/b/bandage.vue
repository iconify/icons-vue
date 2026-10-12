<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="t0gakqb9i"/><path class="w-wbqkerr"/><path class="xbpg6ubac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bandage" /></template>
<style>
.t0gakqb9i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.46 13.24l7.78-7.78a3.75 3.75 0 0 1 5.3 0a3.75 3.75 0 0 1 0 5.3l-7.78 7.78a3.75 3.75 0 0 1-5.3 0a3.75 3.75 0 0 1 0-5.3");
}

.w-wbqkerr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.76 10.94l3.18-3.18a1 1 0 0 1 1.41 0l3.89 3.89a1 1 0 0 1 0 1.41l-3.18 3.18a1 1 0 0 1-1.41 0l-3.89-3.89a1 1 0 0 1 0-1.41");
}

.xbpg6ubac {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.58 16.42h.01m8.83-8.84h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
