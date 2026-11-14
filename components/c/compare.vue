<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmbg5ub0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:compare" /></template>
<style>
.wmbg5ub0a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v19m-2.5-14H3m2.75-2.75L3 7.5l2.75 2.75m8.75 6.25H21m-2.75-2.75L21 16.5l-2.75 2.75");
}

</style>
