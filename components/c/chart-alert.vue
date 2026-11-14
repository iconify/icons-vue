<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dj2i8t18r"/><path class="hu0w6abfe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-alert" /></template>
<style>
.dj2i8t18r {
  d: path("M3.5 3v17.5h7.9");
}

.hu0w6abfe {
  d: path("M6.5 14L10 8.5l3 2.5l6-6.5M18 14l4 7.5h-8Zm0 3.25v1M18 20h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
