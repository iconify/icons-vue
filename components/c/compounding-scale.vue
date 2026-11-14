<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrvscnbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:compounding-scale" /></template>
<style>
.qrvscnbzj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 4.5h13m-6.5 0V20m-4.5 0h9m-14-8.5l3-7l3 7a3 3 0 0 1-6 0Zm13 0l3-7l3 7a3 3 0 0 1-6 0Z");
}

</style>
