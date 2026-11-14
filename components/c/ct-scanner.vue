<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jwy3ciu5d"/><path class="skti6bc6w"/><path class="lgs6j1bcf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ct-scanner" /></template>
<style>
.jwy3ciu5d {
  d: path("M2.5 10a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Z");
}

.lgs6j1bcf {
  d: path("M9 9h12.5v2H9Zm9.5 2v10.5");
}

.skti6bc6w {
  d: path("m5 15l-1 6.5h10L13 15m-7-5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
