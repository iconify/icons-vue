<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krxfw1buy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:jack-cable" /></template>
<style>
.krxfw1buy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 2.5h2.5v6h-2.5ZM9 8.5h6v8H9Zm3 8V18c0 2.25 1.5 3.5 4 3.5h5m-10.25-16h2.5");
}

</style>
