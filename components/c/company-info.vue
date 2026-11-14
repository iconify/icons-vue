<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q4-dod0ry"/><path class="n_ga50b6a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:company-info" /></template>
<style>
.n_ga50b6a {
  d: path("M8 21.5v-4h3v4m7.75-4v4m0-7h.01");
}

.q4-dod0ry {
  d: path("M3.5 2.5h12v19h-12Zm2.75 4h2m2.5 0h2m-6.5 4h2m2.5 0h2m-6.5 4h2m2.5 0h2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
