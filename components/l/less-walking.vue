<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dwnaojfgd"/><path class="i-8kupsxn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:less-walking" /></template>
<style>
.dwnaojfgd {
  d: path("M9.5 4.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm3.75 8.5l-3-3l-3.5 2.5");
}

.i-8kupsxn {
  d: path("m10.5 8.5l-1 5.5l2 3.5v4m-2-7.5L7 18l-2.5 2.5M15 18h6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
