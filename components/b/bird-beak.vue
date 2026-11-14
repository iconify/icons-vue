<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adhv1o4fo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bird-beak" /></template>
<style>
.adhv1o4fo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 5.5C11 5 17.5 8 21 14c-5-2.5-11-3-17-2.5Zm0 8.75q9-.375 15 2.25c-5 2.5-10 3-15 2ZM9 8.5h.01");
}

</style>
