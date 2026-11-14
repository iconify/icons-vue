<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqchfihnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:corner-smoothing" /></template>
<style>
.cqchfihnu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 5.5c6.25 0 8 1.75 8 8s-1.75 8-8 8s-8-1.75-8-8s1.75-8 8-8Zm3.5-3h7.5V10");
}

</style>
