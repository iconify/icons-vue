<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krl5fi02t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:goalkeeper-save" /></template>
<style>
.krl5fi02t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5v19m19-19v19M9 5.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm1.25 6.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm-3.75 9c0-3 2-5 5.5-5s5.5 2 5.5 5M7.25 18.75L9 6.5m7.75 12.25L15 6.5");
}

</style>
