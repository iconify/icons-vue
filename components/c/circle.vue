<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="exj62ibbz"/><path class="psv3yebmi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:circle" /></template>
<style>
.exj62ibbz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 18.75V5.34c0-.98.79-1.79 1.76-1.75a17 17 0 0 1 15.15 15.15c.04.97-.77 1.76-1.75 1.76H5.25a1.75 1.75 0 0 1-1.75-1.75");
}

.psv3yebmi {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 14h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
