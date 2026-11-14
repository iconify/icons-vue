<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="val2izb8g"/><path class="ox9u29-im"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blind-corner" /></template>
<style>
.ox9u29-im {
  d: path("M10 21.5V13a2.5 2.5 0 0 1 2.5-2.5H21m-6.5 8q3.75-4 7.5 0q-3.75 4-7.5 0Zm.75 3.5l6-7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.val2izb8g {
  d: path("M3.5 21.5v-13a5 5 0 0 1 5-5H21");
}

</style>
