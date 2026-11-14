<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ih75qgb5m"/><path class="uz-oo6b5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:incident-merge" /></template>
<style>
.ih75qgb5m {
  d: path("M14.608 17.5H3L11.5 3l5.108 8.713M11.5 8.5V12m0 2.5h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uz-oo6b5p {
  d: path("m15 14l3 3l3-3m-3 3v4.5m-1.75-1.75L18 21.5l1.75-1.75");
}

</style>
