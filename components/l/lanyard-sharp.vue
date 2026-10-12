<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcx9bxh8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lanyard-sharp" /></template>
<style>
.fcx9bxh8m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.75 2.75l6.25 8.5l6.25-8.5m-12 9.5h11.5v9H6.25zm4.25 3h3m-4.25 3h5.5");
}

</style>
