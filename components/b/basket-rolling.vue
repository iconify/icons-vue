<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tru-ovm0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:basket-rolling" /></template>
<style>
.tru-ovm0t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8.5h18L19 17H5Zm4.5 0V7a4.5 4.5 0 0 1 9 0v1.5M6.5 20h.01M10 20h.01M14 20h.01m3.49 0h.01");
}

</style>
