<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="js3wqv9uz"/><path class="lp-knpbsi"/><path class="rdopyh-kh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:foam-roller" /></template>
<style>
.js3wqv9uz {
  d: path("M6.25 5.5H18a3.5 6.5 0 0 1 0 13H6.25");
}

.lp-knpbsi {
  d: path("M2.5 12a3.75 6.5 0 1 0 7.5 0a3.75 6.5 0 1 0-7.5 0Z");
}

.rdopyh-kh {
  d: path("M5.25 12a1 2.5 0 1 0 2 0a1 2.5 0 1 0-2 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
