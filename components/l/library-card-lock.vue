<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zuulbfbir"/><path class="k4b-b2bwv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:library-card-lock" /></template>
<style>
.k4b-b2bwv {
  d: path("M6.5 8.5h4v7l-2-1.5l-2 1.5Zm7 .5H18m-4.5 3.5h1.6M15 17h6v4.5h-6Zm1.25 0v-1a1.75 1.75 0 0 1 3.5 0v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zuulbfbir {
  d: path("M12.2 19H2.5V5h19v8.1");
}

</style>
