<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lozmm92kl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:greenhouse-door" /></template>
<style>
.lozmm92kl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 21.5V4A1.5 1.5 0 0 1 7 2.5h10A1.5 1.5 0 0 1 18.5 4v17.5M3 21.5h18m-9-19v19M5.5 12h13m-3.25 3h.01");
}

</style>
