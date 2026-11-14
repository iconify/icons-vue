<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="po2pceb7v"/><path class="u4xqxx30g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:broadcast-tower-lock" /></template>
<style>
.po2pceb7v {
  d: path("M10 6.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.u4xqxx30g {
  d: path("m6.5 21.5l5.5-13l2.41 5.696M16 3.5a4.5 4.5 0 0 1 0 6m3-7a8 8 0 0 1 0 8m-11-7a4.5 4.5 0 0 0 0 6m-3-7a8 8 0 0 0 0 8m10 7h6v4h-6Zm1.5 0v-1a1.5 1.5 0 0 1 3 0v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
