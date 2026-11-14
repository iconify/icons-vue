<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uqt1gyb_t"/><path class="s27o0-bmf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gut-health" /></template>
<style>
.s27o0-bmf {
  d: path("M6.75 6.5h5.5c1.25 0 1.25 2.75 0 2.75H8C6.5 9.25 6.5 12 8 12h4.25c.232 0 .421.095.567.25m-1.157 2.5H10v2.75m8 4.25V18m0 .5c-2.25 0-3.5-1.25-3.5-3.5c2.25 0 3.5 1.25 3.5 3.5Zm0-1c0-2 1.25-3.25 3.5-3.25c0 2.25-1.25 3.25-3.5 3.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uqt1gyb_t {
  d: path("M4 17.5V5.25C4 4 5 3 6.5 3h7c1.25 0 2.25 1 2.25 2.25v7.039");
}

</style>
