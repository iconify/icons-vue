<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n93dmi3qb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:conductor-baton-sharp" /></template>
<style>
.n93dmi3qb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.31 20.69a2.75 1.6-45 1 0 3.88-3.88a2.75 1.6-45 1 0-3.88 3.88Zm3.94-3.94L19 5m2 4.5c.5 5-3.5 10.5-9.5 11");
}

</style>
