<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lo0p7bciv"/><path class="n35j_l55i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cpu-sharp" /></template>
<style>
.lo0p7bciv {
  d: path("M6.25 6.25h11.5v11.5H6.25z");
}

.n35j_l55i {
  d: path("M9.5 9.5h5v5h-5zm0-6.75v3.5m5-3.5v3.5m-5 11.5v3.5m5-3.5v3.5M2.75 9.5h3.5m-3.5 5h3.5m11.5-5h3.5m-3.5 5h3.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
