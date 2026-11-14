<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uyx3iobqo"/><path class="l066_12vs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:husky-dog" /></template>
<style>
.l066_12vs {
  d: path("M9.5 6.5L12 12l2.5-5.5m-6.5 6h.01m7.99 0h.01M12 17h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uyx3iobqo {
  d: path("m3.5 10.5l1-8l5 4h5l5-4l1 8c0 6-4 11-8.5 11s-8.5-5-8.5-11Z");
}

</style>
