<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sf99twbfm"/><path class="he_knpd7u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:anatomy" /></template>
<style>
.he_knpd7u {
  d: path("m12 18.5l-3.25-3.25A2 2 0 0 1 12 12.5a2 2 0 0 1 3.25 2.75Z");
}

.sf99twbfm {
  d: path("M10 4.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM5.25 21.5V12a3 3 0 0 1 3-3h7.5a3 3 0 0 1 3 3v9.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
