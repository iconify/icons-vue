<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lp6docbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chevrons-left-right-sharp" /></template>
<style>
.lp6docbrt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.25 7l-3 5l3 5m11.5-10l3 5l-3 5m-8-10l-3 5l3 5m4.5-10l3 5l-3 5");
}

</style>
