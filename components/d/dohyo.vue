<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdgu3ybil"/><path class="gz41qiq8d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dohyo" /></template>
<style>
.gz41qiq8d {
  d: path("M13.618 5.963a6.25 6.25 0 0 1 4.419 4.419m0 3.236a6.25 6.25 0 0 1-4.419 4.419m-3.236 0a6.25 6.25 0 0 1-4.419-4.419m0-3.236a6.25 6.25 0 0 1 4.419-4.419");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zdgu3ybil {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Z");
}

</style>
