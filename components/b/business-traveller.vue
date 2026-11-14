<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5n2u_r-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:business-traveller" /></template>
<style>
.k5n2u_r-d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 6.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM2.5 21c0-4 3.25-7 7-7c.963 0 1.85.151 2.661.412M15 16.5h6.5v5H15Zm2 0V15h2.5v1.5");
}

</style>
