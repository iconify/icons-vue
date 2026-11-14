<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyijcqbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:interview-panel" /></template>
<style>
.oyijcqbwv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11.5h19m-18-2.75V5.5a1.5 1.5 0 0 1 3 0v3.25m4 0V5.5a1.5 1.5 0 0 1 3 0v3.25m4 0V5.5a1.5 1.5 0 0 1 3 0v3.25m-12 5.5h7v4.5h-7Zm1 4.5v2.75m5-2.75v2.75");
}

</style>
