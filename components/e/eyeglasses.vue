<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cep-lob_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:eyeglasses" /></template>
<style>
.cep-lob_x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9h7.25v2.75C10.25 13.75 9 15 7 15h-.75C4.25 15 3 13.75 3 11.75Zm18 0h-7.25v2.75c0 2 1.25 3.25 3.25 3.25h.75c2 0 3.25-1.25 3.25-3.25Zm-10.75 1.25c.75-.75 2.75-.75 3.5 0");
}

</style>
