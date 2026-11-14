<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6r93rh3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cat-loaf" /></template>
<style>
.c6r93rh3z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 19.5V15A5.5 5.5 0 0 1 9 9.5h3.5V5l3 2.5h2l3-2.5v14.5Zm14-8h.01m-4.01 5h4");
}

</style>
