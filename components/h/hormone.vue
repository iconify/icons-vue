<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v6unoccll"/><path class="sqqt1indn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hormone" /></template>
<style>
.sqqt1indn {
  d: path("m16 9.5l3.897 2.25v4.5L16 18.5l-3.897-2.25v-4.5Zm0 0v-3l3-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v6unoccll {
  d: path("m8.25 9.5l3.897 2.25v4.5L8.25 18.5l-3.897-2.25v-4.5Z");
}

</style>
