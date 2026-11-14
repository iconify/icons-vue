<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uza2veb8u"/><path class="v5c68rj7q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:binoculars-science" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uza2veb8u {
  d: path("M2.5 15.5V7a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v8.5m3 0V7a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v8.5");
}

.v5c68rj7q {
  d: path("M2.5 15.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm11 0a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm-3-6.5h3");
}

</style>
