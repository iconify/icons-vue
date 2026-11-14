<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvyefv1jd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:code-injection" /></template>
<style>
.fvyefv1jd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7 12l-4 3.75l4 3.75M17 12l4 3.75l-4 3.75m-7-15h4v7h-4Zm-.5-2h5m-2.5 0v2m0 7V16");
}

</style>
