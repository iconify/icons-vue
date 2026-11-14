<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bip5xy82q"/><path class="xm7mgjkse"/><path class="albr56pca"/><path class="bkm_4czst"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:canned-food" /></template>
<style>
.albr56pca {
  d: path("M13.5 9.75v10.5a3.75 1.25 0 0 0 7.5 0V9.75M3 10a3.75 1.25 0 0 0 7.5 0M3 15.5a3.75 1.25 0 0 0 7.5 0");
}

.bip5xy82q {
  d: path("M3 5.25a3.75 1.25 0 1 0 7.5 0a3.75 1.25 0 1 0-7.5 0Z");
}

.bkm_4czst {
  d: path("M13.5 13.5a3.75 1.25 0 0 0 7.5 0m-7.5 3.75a3.75 1.25 0 0 0 7.5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xm7mgjkse {
  d: path("M3 5.25v15a3.75 1.25 0 0 0 7.5 0v-15m3 4.5a3.75 1.25 0 1 0 7.5 0a3.75 1.25 0 1 0-7.5 0Z");
}

</style>
