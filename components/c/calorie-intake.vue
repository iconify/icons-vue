<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m_1pkp_ec"/><path class="xr-18jbla"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:calorie-intake" /></template>
<style>
.m_1pkp_ec {
  d: path("M8.5 19.75c-3 0-5.25-2-5.25-4.75c0-3 2.75-4.5 3.25-8c1.25 1 2 2.5 2 4c1-.5 2-1.5 2-2.5c2 1.5 3.25 3.75 3.25 6.5s-2.25 4.75-5.25 4.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xr-18jbla {
  d: path("M8.5 19.75c-1 0-2-.75-2-1.75c0-1.5 1.25-2 2-3.5c.75 1.5 2 2 2 3.5c0 1-1 1.75-2 1.75ZM17 4v4a2 2 0 0 0 4 0V4m-2 0v16");
}

</style>
