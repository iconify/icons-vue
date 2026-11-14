<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s--u4ybvs"/><path class="yz4mlsb9u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:allergy-test" /></template>
<style>
.s--u4ybvs {
  d: path("m2.5 8.5l9 .75c1 0 1.75-.5 2.5-1.25l1.5-1.5c.75-.75 2-.25 1.75.75L16.75 9H19c1.4 0 2.5 1.1 2.5 2.5V13c0 1.4-1.1 2.5-2.5 2.5l-7.5-.5l-9 1m19-3.75H19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yz4mlsb9u {
  d: path("M3.75 12.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm3.5 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm3.5 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

</style>
