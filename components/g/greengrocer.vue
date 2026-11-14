<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gbcst-9nh"/><path class="fkrtfkdyw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:greengrocer" /></template>
<style>
.fkrtfkdyw {
  d: path("M7 13h4v7.5H7Zm11 2.75c-1.5-1.25-3.25-.5-3.25 1.75s1.75 4 3.25 3.25c1.5.75 3.25-1 3.25-3.25s-1.75-3-3.25-1.75Zm0 0L17.25 14");
}

.gbcst-9nh {
  d: path("M3 6.5L4.5 3h15L21 6.5m-18 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0M4.5 9v11.5h8.1m6.9-8.3V9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
