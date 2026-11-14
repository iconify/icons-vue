<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yz4fhdc2n"/><path class="cw8duabuu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:job-board" /></template>
<style>
.cw8duabuu {
  d: path("M6 10.5h3.75a.75.75 0 0 1 .75.75v7.25a.75.75 0 0 1-.75.75H6a.75.75 0 0 1-.75-.75v-7.25A.75.75 0 0 1 6 10.5Zm-.75 1.75h5.25m-3.75 2.5h2m-2 2.25h1m6.5-6.5H18a.75.75 0 0 1 .75.75v7.25a.75.75 0 0 1-.75.75h-3.75a.75.75 0 0 1-.75-.75v-7.25a.75.75 0 0 1 .75-.75Zm-.75 1.75h5.25M15 14.75h2M15 17h1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yz4fhdc2n {
  d: path("M2.5 2.5h19v19h-19Zm0 5.25h19M5.5 5h.01m2.74 0h.01M11 5h.01");
}

</style>
