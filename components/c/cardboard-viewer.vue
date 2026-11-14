<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a6hwopb5g"/><path class="oi4acibdj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cardboard-viewer" /></template>
<style>
.a6hwopb5g {
  d: path("M4.5 5.5h15a2 2 0 0 1 2 2v9a2 2 0 0 1-2 2h-4.75l-1.5-2.75h-2.5l-1.5 2.75H4.5a2 2 0 0 1-2-2v-9a2 2 0 0 1 2-2Z");
}

.oi4acibdj {
  d: path("M5.25 11a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm9 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
