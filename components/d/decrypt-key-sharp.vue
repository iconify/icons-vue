<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="o9ebbcbgw"/><circle class="ptricrbgn"/><path class="wf96h2k6o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:decrypt-key-sharp" /></template>
<style>
.o9ebbcbgw {
  d: path("M2.75 2.75h18.5v9.5H2.75zM6.5 6.5h11m-11 3h7");
}

.ptricrbgn {
  cx: 6px;
  cy: 17.75px;
  r: 3.25px;
}

.wf96h2k6o {
  d: path("M9.25 17.75h11.5m-2.25 0v2.5m-2.75-2.5v1.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
