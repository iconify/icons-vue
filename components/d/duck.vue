<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="h4cpqh-6i"/><path class="jabqh1a-c"/><path class="t0v9_ux4u"/><path class="cqaqaeb0e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:duck" /></template>
<style>
.cqaqaeb0e {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 15.5c1.75 1.25 4.25 1.25 6 0");
}

.h4cpqh-6i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 11.75c1.75 1.25 3.75 1.5 6.25 1c-1-.75-1.5-2.25-1.5-3.5a4 4 0 0 1 8 0c0 1.25-.5 2.5-1.25 3.25h2.5c1.5 0 2.75 1.25 2.75 2.75c0 3-2.75 5-6.25 5h-5c-3.25 0-5.5-3-5.5-8.5");
}

.jabqh1a-c {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.75 8.25h3.75a.6.6 0 0 1 .45 1l-1.2 1.3c-.75.8-1.85 1.15-2.9.9Z");
}

.t0v9_ux4u {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 8.5h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
