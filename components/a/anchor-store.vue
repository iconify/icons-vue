<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mwwwzccsm"/><path class="j10ivxb2m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:anchor-store" /></template>
<style>
.j10ivxb2m {
  d: path("M8.5 5H11v2H8.5ZM13 5h2.5v2H13ZM8.5 9.25H11v2H8.5Zm4.5 0h2.5v2H13ZM5.5 21.5h13");
}

.mwwwzccsm {
  d: path("M5.5 14V2.5h13V14M3 16.75L4.5 14h15l1.5 2.75m-18 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
