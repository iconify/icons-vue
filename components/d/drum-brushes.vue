<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="far2wzbyh"/><path class="bq-2h04fa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drum-brushes" /></template>
<style>
.bq-2h04fa {
  d: path("M3 16.5v2a9 2.5 0 0 0 18 0v-2m-5-5.25l-9-6m0 0L5.25 2.5L3.5 4.75Zm1 6l9-6m0 0l1.75-2.75l1.75 2.25Z");
}

.far2wzbyh {
  d: path("M3 16.5a9 2.5 0 1 0 18 0a9 2.5 0 1 0-18 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
