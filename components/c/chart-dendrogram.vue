<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zygma10tq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-dendrogram" /></template>
<style>
.zygma10tq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 12h5m0-5v10m0-10H14M8.5 17H14m0-12.5v5m0 5v5m0-15h6.5m-6.5 5h6.5m-6.5 5h6.5m-6.5 5h6.5");
}

</style>
