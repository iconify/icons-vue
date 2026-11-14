<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_psw1y4g"/><path class="u_f63mvmd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:key-square" /></template>
<style>
.j_psw1y4g {
  d: path("M3 3h18v18H3Z");
}

.u_f63mvmd {
  d: path("M6 12a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm5 0h7m-3 0v2.75M18 12v3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
