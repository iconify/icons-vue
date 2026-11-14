<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mzdagcixu"/><path class="ow_mg0g_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:interview-scorecard" /></template>
<style>
.mzdagcixu {
  d: path("M3.5 2.5h17v19h-17Zm10 0v19M3.5 9h17m-17 6h17M6 5.75h5M6 12h5m-5 6.25h5");
}

.ow_mg0g_c {
  d: path("m15.5 12l1 1l2-2m-3 7.25l1 1l2-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
