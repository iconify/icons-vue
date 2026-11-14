<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-el7uo-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:counterfeit-check" /></template>
<style>
.h-el7uo-u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.157 3.015l2.828 2.828a1.5 1.5 0 0 1 0 2.121L7.964 19.985a1.5 1.5 0 0 1-2.121 0l-2.828-2.828a1.5 1.5 0 0 1 0-2.121L15.036 3.015a1.5 1.5 0 0 1 2.121 0Zm-8.132 6.01l4.95 4.95M14.75 18l2 2L21 15.75");
}

</style>
