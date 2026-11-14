<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ot5hokbwa"/><path class="m-uxk6b8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:genre-battle-royale" /></template>
<style>
.m-uxk6b8o {
  d: path("m7 11l5 5.5l5-5.5m-2.541-8.176a9.5 9.5 0 0 1 6.717 6.717m0 4.918a9.5 9.5 0 0 1-6.717 6.717m-4.918 0a9.5 9.5 0 0 1-6.717-6.717m0-4.918a9.5 9.5 0 0 1 6.717-6.717");
}

.ot5hokbwa {
  d: path("M7 11a5 4.5 0 0 1 10 0a1.625 1 0 0 1-3.25 0a1.75 1 0 0 1-3.5 0A1.625 1 0 0 1 7 11Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
