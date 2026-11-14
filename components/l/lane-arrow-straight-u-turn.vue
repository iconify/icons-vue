<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cv49yqkag"/><path class="s8epzqb0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lane-arrow-straight-u-turn" /></template>
<style>
.cv49yqkag {
  d: path("M15.5 21.5V3m-5 5l5-5l5 5m-5 4h-6a4 4 0 0 0-4 4v4.5");
}

.s8epzqb0c {
  d: path("m3 18l2.5 2.5L8 18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
