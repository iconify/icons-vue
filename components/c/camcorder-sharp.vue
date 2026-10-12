<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="epe7d9bhf"/><path class="nczoc976s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:camcorder-sharp" /></template>
<style>
.epe7d9bhf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.75h3.5v7.5h-3.5zm3.5 3.75H8.5m0-4.75h9v10.5h-9zm9 2.25h3.75v6H17.5z");
}

.nczoc976s {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11.5 10h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
