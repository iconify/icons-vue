<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="df4gofoar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:genre-fantasy-film" /></template>
<style>
.df4gofoar {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16 3.25l1.25 3l3.25.25L18 8.75l.75 3L16 10l-2.75 1.75l.75-3l-2.5-2.25l3.25-.25ZM3.5 20.5l7-7");
}

</style>
