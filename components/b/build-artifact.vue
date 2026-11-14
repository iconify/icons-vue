<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wy7naubms"/><path class="vzirhcbtt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:build-artifact" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vzirhcbtt {
  d: path("M2.5 6.75L11 11l8.5-4.25M11 11v8.5m5.25-14.75L7.75 9.5");
}

.wy7naubms {
  d: path("m11 2.5l8.5 4.25v8.5L11 19.5l-8.5-4.25v-8.5Z");
}

</style>
