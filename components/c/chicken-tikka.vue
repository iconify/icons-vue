<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="muiuvnb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chicken-tikka" /></template>
<style>
.muiuvnb0q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 14.025L9.975 16.5L7.5 18.975L5.025 16.5Zm4.5-4.5L14.475 12L12 14.475L9.525 12Zm4.5-4.5L18.975 7.5L16.5 9.975L14.025 7.5ZM3.5 20.5l2.75-2.75m2.5-2.5l2-2m2.5-2.5l2-2m2.5-2.5L20.5 3.5");
}

</style>
