<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gry5v8u2o"/><path class="vnh1r6qxc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bee-skep" /></template>
<style>
.gry5v8u2o {
  d: path("M4 20.5C4 12 7 4 12 4s8 8 8 16.5Zm.5-5h15M5.75 10h12.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vnh1r6qxc {
  d: path("M10 20.5a2 2 0 0 1 4 0");
}

</style>
