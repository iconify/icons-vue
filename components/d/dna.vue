<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hxjzx0sgy"/><path class="fwqofdcqf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dna" /></template>
<style>
.fwqofdcqf {
  d: path("M17 3c0 4.5-10 4.5-10 9s10 4.5 10 9M7.5 4.5h9M7 12h10m-9.5 7.5h9");
}

.hxjzx0sgy {
  d: path("M7 3c0 4.5 10 4.5 10 9S7 16.5 7 21");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
