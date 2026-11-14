<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="trh2ghbkw"/><path class="d70ir4dhj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leave-rejected" /></template>
<style>
.d70ir4dhj {
  d: path("M10 6.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm4 0h3.5m-7.75 6.25l4.5 4.5m0-4.5l-4.5 4.5");
}

.trh2ghbkw {
  d: path("M6.5 2.5h11v19h-11Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
