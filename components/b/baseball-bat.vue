<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8z--hs6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baseball-bat" /></template>
<style>
.h8z--hs6u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.338 18.187l5.303-5.303l7.955-10.783l5.303 5.303l-10.783 7.955l-5.303 5.303Zm-.884-.884l4.243 4.243");
}

</style>
