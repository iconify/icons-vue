<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l087an1gy"/><path class="rhkxz0bfq"/><path class="urzg_xb2g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:home-care" /></template>
<style>
.l087an1gy {
  d: path("M2.5 11L12 3l9.5 8");
}

.rhkxz0bfq {
  d: path("M5 9v10.5c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2V9M7.5 12v7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.urzg_xb2g {
  d: path("M7.5 15.5h7.75c.75 0 1.25.5 1.25 1.25V19m-7.25-6.25h3v1.5h-3Z");
}

</style>
