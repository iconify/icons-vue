<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ebotri-1n"/><path class="cu5_hdehu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:back-button-focus" /></template>
<style>
.cu5_hdehu {
  d: path("M8.75 15a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0ZM6 12.25v-2h2m8 0h2v2m0 5.5v2h-2m-8 0H6v-2");
}

.ebotri-1n {
  d: path("M2.5 7.5H7l1.5-4H14l1.5 4H19a2.5 2.5 0 0 1 2.5 2.5v11.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
