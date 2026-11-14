<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dtjrp_bfl"/><path class="mzdlqyw0t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coat-check" /></template>
<style>
.dtjrp_bfl {
  d: path("M4 3h16m-8 0v3m0 0L7.5 7.5L5 21h14L16.5 7.5Z");
}

.mzdlqyw0t {
  d: path("m9 7l3 5l3-5m-3 5v9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
