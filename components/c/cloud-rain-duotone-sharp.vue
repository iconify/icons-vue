<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w3locczqy"/><path class="m-nr0qbve"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-rain-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m-nr0qbve {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 15a4 4 0 1 1 0-8c2-6 11-5 11 2a3 3 0 0 1 0 6Zm1 3v3m4-3v3m4-3v3");
}

.w3locczqy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6.295 6.049a6.58 6.58 0 0 1 2.773-3.121a6.75 6.75 0 0 1 4.33-.792c2.381.358 4.323 1.911 5.151 4.18c.21.58.346 1.184.407 1.799A4 4 0 0 1 18 16H7a5 5 0 0 1-4.987-4.646a5 5 0 0 1 4.282-5.305");
}

</style>
