<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ufuby1bfx"/><path class="uxk8nvd9q"/><path class="iymx8nbvx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:air-fryer-sharp" /></template>
<style>
.iymx8nbvx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 13.25h3.75v6.25");
}

.ufuby1bfx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 2.75H17v18.5H3.25zm0 8H17");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.uxk8nvd9q {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.125 6.75h.01");
}

</style>
