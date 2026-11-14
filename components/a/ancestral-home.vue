<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hee4h9bjd"/><path class="vhnf_mbwi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ancestral-home" /></template>
<style>
.hee4h9bjd {
  d: path("M10.444 20.5H3.5v-10L12 3.25l8.5 7.25v2.456");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vhnf_mbwi {
  d: path("m18 14.25l3.5 5.25h-7Zm0 5.25v2.25");
}

</style>
