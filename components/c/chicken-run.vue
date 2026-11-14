<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r4nmxrb0m"/><path class="m9r7aqb6z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chicken-run" /></template>
<style>
.m9r7aqb6z {
  d: path("M6 20v-2.5a1.5 1.5 0 0 1 3 0V20");
}

.r4nmxrb0m {
  d: path("m3 10l4.5-5.5L12 10v10H3Zm9 2.5h9m-9 4h9m-4.5-7V20M21 9.5V20");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
