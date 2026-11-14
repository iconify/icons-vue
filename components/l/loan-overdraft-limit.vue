<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyridbsdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:loan-overdraft-limit" /></template>
<style>
.lyridbsdc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 5.5l3.5 1l3 4l3 4.5l2 1.75h7.5m-19 2.75h19v2h-19Zm0-9H4m8.5 0H14m2.5 0H18m2 0h1.5");
}

</style>
