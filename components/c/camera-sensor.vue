<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rhqzuob8o"/><path class="etwnqi58a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:camera-sensor" /></template>
<style>
.etwnqi58a {
  d: path("M7 8.5h10v7H7Zm1-6v3m4-3v3m4-3v3m-8 13v3m4-3v3m4-3v3");
}

.rhqzuob8o {
  d: path("M4 5.5h16v13H4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
