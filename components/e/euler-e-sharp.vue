<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pa_dz-bsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:euler-e-sharp" /></template>
<style>
.pa_dz-bsy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 14.25h10c0-3.25-2-5.5-4.75-5.5S4 11.25 4 14.5s2.25 5.75 5.25 5.75h2.65l1.6-2m2-8.75c2 0 3.5-1.5 4.75-5.75");
}

</style>
