<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pq6ve4mbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:binoculars-sharp" /></template>
<style>
.pq6ve4mbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 16.75v-11h7.5v11a3.75 3.75 0 0 1-7.5 0Zm11 0v-11h7.5v11a3.75 3.75 0 0 1-7.5 0Zm-3.5-7.25h3.5v3h-3.5zm-7.5 4h7.5m3.5 0h7.5");
}

</style>
