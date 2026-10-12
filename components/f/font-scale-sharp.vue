<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkxkadbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:font-scale-sharp" /></template>
<style>
.pkxkadbwx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20L6 11.25L9.25 20M3.9 17h4.2m2.65 3L16 4.75L21.25 20m-8.5-5.5h6.5");
}

</style>
