<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d4f7esbvm"/><path class="buny-nbzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cell-cycle" /></template>
<style>
.buny-nbzt {
  d: path("M18.75 2.75v2.5h-2.5m-4.25 5a3 3 0 1 0 0 3.5a3 3 0 1 0 0-3.5Z");
}

.d4f7esbvm {
  d: path("M21.5 12a9.5 9.5 0 1 1-2.75-6.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
