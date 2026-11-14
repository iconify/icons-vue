<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dxl9y9b0l"/><path class="tqd-eiexg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hydrogen-molecule" /></template>
<style>
.dxl9y9b0l {
  d: path("M2.5 16.75a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0Zm9.5-9.5a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0Zm-1.25 6l2.5-2.5");
}

.tqd-eiexg {
  d: path("M4.75 16.75a2.5 2.5 0 0 1 2.5-2.5m7-7a2.5 2.5 0 0 1 2.5-2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
