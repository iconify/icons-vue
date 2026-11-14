<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knaen828t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fire-ladder-sign" /></template>
<style>
.knaen828t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 2.5v19m8-19v19m-8-15h8M4 11h8m-8 4.5h8M4 20h8m6.5-5.75c2 1.75 3.25 3.25 3.25 5S20.25 22 18.5 22s-3.25-1-3.25-2.75c0-1.5 1-2.5 1.75-3.25c0 1.25.5 2 1.25 2.25c0-1.5-.25-2.75.25-4Z");
}

</style>
