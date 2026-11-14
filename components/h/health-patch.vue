<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b-kichb8c"/><path class="uziuzvbpj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:health-patch" /></template>
<style>
.b-kichb8c {
  d: path("M2.75 14.5a6.75 6.75 0 1 0 13.5 0a6.75 6.75 0 1 0-13.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uziuzvbpj {
  d: path("M6.5 14.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm5.394-8.935a9.25 9.25 0 0 1 6.541 6.541m-4.916-8.647a11.75 11.75 0 0 1 7.022 7.022");
}

</style>
