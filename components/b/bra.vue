<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0cztxbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bra" /></template>
<style>
.g0cztxbra {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 19.5v-2c0-4 3-7.25 6-8c2 2 3.25 5 3.5 8c.25-3 1.5-6 3.5-8c3 .75 6 4 6 8v2Zm6-10l-1-5m8 5l1-5m-4.5 13v2");
}

</style>
