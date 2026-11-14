<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_psw1y4g"/><path class="hj0bgbc3r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:consent-preferences" /></template>
<style>
.hj0bgbc3r {
  d: path("M6.5 7.5h1a1.5 1.5 0 1 1 3 0a1.5 1.5 0 1 1-3 0m3 0h7M6.5 12h7a1.5 1.5 0 1 1 3 0a1.5 1.5 0 1 1-3 0m3 0h1m-11 4.5h3a1.5 1.5 0 1 1 3 0a1.5 1.5 0 1 1-3 0m3 0h5");
}

.j_psw1y4g {
  d: path("M3 3h18v18H3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
