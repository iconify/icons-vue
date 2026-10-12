<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="cbckphyom"/><path class="nyb4gfb3a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chemistry-sharp" /></template>
<style>
.cbckphyom {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 2.75h4v6.33a6.25 6.25 0 0 1 4.23 6.42H5.77A6.25 6.25 0 0 1 10 9.08ZM5.77 15.5h12.46a6.25 6.25 0 0 1-12.46 0Z");
}

.nyb4gfb3a {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.75 4h.01m1.99 3.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
