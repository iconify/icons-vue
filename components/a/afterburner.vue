<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pr50gmb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:afterburner" /></template>
<style>
.pr50gmb8b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 6l7 2v8l-7 2ZM16 8.5c2.5 0 4 2 5.5 3.5c-1.5 1.5-3 3.5-5.5 3.5a3.5 3.5 0 0 1 0-7ZM6 7v10");
}

</style>
