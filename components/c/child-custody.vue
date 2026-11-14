<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j81sz7ifd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:child-custody" /></template>
<style>
.j81sz7ifd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 7a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0ZM2.5 21v-3.5a4.5 4.5 0 0 1 9 0V21M16 11a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-1.5 10v-1.5a3.5 3.5 0 0 1 7 0V21m-10-3.5l3 2");
}

</style>
