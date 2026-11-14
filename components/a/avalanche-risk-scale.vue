<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cc74-z4xm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:avalanche-risk-scale" /></template>
<style>
.cc74-z4xm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 17.5h-10l6-14l3.5 7L14.5 7l1.906 2.621M18 12.75l4 8.75h-8Zm0 4V19");
}

</style>
