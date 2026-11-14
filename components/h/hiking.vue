<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcliaxtbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hiking" /></template>
<style>
.dcliaxtbw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm1 3.5l-2 6l3 3V21m-3-7.5l-2 4l-2.5 3m1-13h3.5V13H7Zm5 2l4.5 1.5m.75-2.5l1.5 12.5");
}

</style>
