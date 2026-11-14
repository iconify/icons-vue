<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i95qqrb8u"/><path class="gm1-54msb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dna-search" /></template>
<style>
.gm1-54msb {
  d: path("M13.5 2.5c0 5-10 5-10 9.5c0 3.897 7.5 4.419 9.51 7.737m.141.256c.223.448.349.946.349 1.507M4.5 5h8m-9 7h10m1.75 5.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm4 1.75L21 21");
}

.i95qqrb8u {
  d: path("M3.5 2.5c0 5 10 5 10 9.5s-10 4.5-10 9.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
