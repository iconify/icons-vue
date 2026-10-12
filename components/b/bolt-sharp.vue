<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9a4w5b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bolt-sharp" /></template>
<style>
.a9a4w5b8i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 2.75h12v5H6zm3.5 5h5v13.5h-5zm.75-5v5m3.5-5v5m-4.25 4.5l5-1.25m-5 4.75l5-1.25m-5 4.75l5-1.25");
}

</style>
