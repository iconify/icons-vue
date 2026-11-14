<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qecaf_bxa"/><path class="lkz2-8bjm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crochet-granny-square" /></template>
<style>
.lkz2-8bjm {
  d: path("M8 8h8v8H8Z");
}

.qecaf_bxa {
  d: path("M4.5 4.5a2.5 2.5 0 0 1 5 0a2.5 2.5 0 0 1 5 0a2.5 2.5 0 0 1 5 0a2.5 2.5 0 0 1 0 5a2.5 2.5 0 0 1 0 5a2.5 2.5 0 0 1 0 5a2.5 2.5 0 0 1-5 0a2.5 2.5 0 0 1-5 0a2.5 2.5 0 0 1-5 0a2.5 2.5 0 0 1 0-5a2.5 2.5 0 0 1 0-5a2.5 2.5 0 0 1 0-5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
