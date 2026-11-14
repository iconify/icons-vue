<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mhri5vbhs"/><path class="yubqskb4p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:grafting-tape" /></template>
<style>
.mhri5vbhs {
  d: path("M2.5 11a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yubqskb4p {
  d: path("M10 18.5h11.5l-1.25-2.25H15.5M7 11a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

</style>
