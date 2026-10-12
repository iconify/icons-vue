<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="z8msbccam"/><circle class="rip_g9cqu"/><path class="q9-aapbwy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:circuit-sharp" /></template>
<style>
.q9-aapbwy {
  d: path("M10.5 2.75v4m3-3v2");
}

.rip_g9cqu {
  cx: 12px;
  cy: 19.25px;
  r: 2px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z8msbccam {
  d: path("M10.5 4.75H3.75v14.5H10m3.5-14.5h6.75v14.5H14");
}

</style>
