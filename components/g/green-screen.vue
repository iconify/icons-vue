<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0on51nhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:green-screen" /></template>
<style>
.s0on51nhx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3h19M4 3v13.5M20 3v13.5M8.75 9a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0ZM5.5 21.5c0-3.75 3-6.5 6.5-6.5s6.5 2.75 6.5 6.5");
}

</style>
