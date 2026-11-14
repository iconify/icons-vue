<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d894yzp-x"/><path class="h52ad9wiz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:landslide" /></template>
<style>
.d894yzp-x {
  d: path("M2.5 20.5v-16H6l2.5 6c3.5 1 7.5 4.5 13 5.5v4.5Z");
}

.h52ad9wiz {
  d: path("m11.5 6l5.5 5.5m-3.5 0H17V8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
