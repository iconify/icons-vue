<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-jd70b2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:club-suit" /></template>
<style>
.k-jd70b2t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 15.75L9.5 20.5h5L13 15.75a4 4 0 1 0 1.75-5.5a4 4 0 1 0-5.5 0a4 4 0 1 0 1.75 5.5Z");
}

</style>
