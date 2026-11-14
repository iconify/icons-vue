<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9w164rna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:jewellery-insurance" /></template>
<style>
.n9w164rna {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 15.25a5.25 5.25 0 1 0 10.5 0a5.25 5.25 0 1 0-10.5 0ZM8.5 6L10 3.5h4L15.5 6L12 9Z");
}

</style>
