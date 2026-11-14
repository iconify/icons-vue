<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pivqg_bkg"/><path class="gohp-6a8d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:engine-run-up-area" /></template>
<style>
.gohp-6a8d {
  d: path("M6.5 7.75h8l3.5 2.5v3.5l-3.5 2.5h-8");
}

.pivqg_bkg {
  d: path("M2.5 7V2.5H7m10 0h4.5V7m0 10v4.5H17m-10 0H2.5V17m2-5a2 4.25 0 1 0 4 0a2 4.25 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
