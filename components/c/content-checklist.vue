<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ll0veebzd"/><path class="kovn14j2i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:content-checklist" /></template>
<style>
.kovn14j2i {
  d: path("M14 2.5v5h5M7.75 11.75L9 13l2-2m2.75 1h2.5m-8.5 4.75L9 18l2-2m2.75 1h2.5");
}

.ll0veebzd {
  d: path("M14 2.5H7c-1.1 0-2 .9-2 2v15c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2v-12Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
