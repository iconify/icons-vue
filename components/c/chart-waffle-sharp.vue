<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yq3fyoi2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-waffle-sharp" /></template>
<style>
.yq3fyoi2w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h2.9v2.9h-2.9zm5.2 0h2.9v2.9h-2.9zm5.2 0h2.9v2.9h-2.9zm5.2 0h2.9v2.9h-2.9zm-15.6 5.2h2.9v2.9h-2.9zm5.2 0h2.9v2.9h-2.9zm5.2 0h2.9v2.9h-2.9zm5.2 0h2.9v2.9h-2.9zm-15.6 5.2h2.9v2.9h-2.9zm5.2 0h2.9v2.9h-2.9zm5.2 0h2.9v2.9h-2.9zm5.2 0h2.9v2.9h-2.9zm-15.6 5.2h2.9v2.9h-2.9zm5.2 0h2.9v2.9h-2.9zm5.2 0h2.9v2.9h-2.9zm5.2 0h2.9v2.9h-2.9z");
}

</style>
