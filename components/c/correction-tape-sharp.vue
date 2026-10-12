<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="bmpqmkbxc"/><path class="qxyd16gsh"/><path class="h3qkj9bop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:correction-tape-sharp" /></template>
<style>
.bmpqmkbxc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 4.5h10l.64 1.35l1.22 2.55l.64 1.35l1.48.26l1.29.23l1.48.26v3l-1.48.26l-1.29.23l-1.48.26l-.64 1.35l-1.22 2.55l-.64 1.35H3v-15z");
}

.h3qkj9bop {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 12h.01");
}

.qxyd16gsh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 8.5a3.5 3.5 0 1 1 0 7a3.5 3.5 0 1 1 0-7");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
