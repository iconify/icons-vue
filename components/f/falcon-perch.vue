<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ujhfwgy3x"/><path class="vq5ph8i9x"/><path class="qq1oo5bra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:falcon-perch" /></template>
<style>
.qq1oo5bra {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.75 7.5c1.5.6 3.25.6 4.75-.25M9.75 10.5c1 2.25 2.5 4 4.5 5m-3 5.25h9m-6.75-3v3");
}

.ujhfwgy3x {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.75 3c1.75 0 3 1 3.4 2.4l1.35.6a.5.5 0 0 1 .1.85l-1.2.9c.6 1 .85 2.25.85 3.75c0 2.9-1.25 5.25-3.25 6.25h-4L8 21a.6.6 0 0 1-1-.6L8.75 17c-.75-1.25-1.1-2.75-1.1-4.5c0-3.9 2-6.5 4.3-7.9c.4-1 1-1.6 1.8-1.6");
}

.vq5ph8i9x {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.25 5.25h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
