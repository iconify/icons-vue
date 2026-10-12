<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="thw4kubbs"/><circle class="xe3kkrg5a"/><path class="xpec6eu_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:av-receiver-sharp" /></template>
<style>
.thw4kubbs {
  d: path("M2.75 6.25h18.5v10.5H2.75zm3.5 3.5h5m-5 3.5h3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xe3kkrg5a {
  cx: 16.5px;
  cy: 11.5px;
  r: 2.25px;
}

.xpec6eu_k {
  d: path("M5.75 16.75v2m12.5-2v2");
}

</style>
