<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ih-11-b1l"/><path class="mcy7tn5wc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-pictogram" /></template>
<style>
.ih-11-b1l {
  fill: currentColor;
  d: path("M3.25 7a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM2.5 19v-5.5a2.5 2.5 0 0 1 5 0V19Zm7.75-12a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM9.5 19v-5.5a2.5 2.5 0 0 1 5 0V19Z");
}

.mcy7tn5wc {
  d: path("M17.25 7a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm-.75 12v-5.5a2.5 2.5 0 0 1 5 0V19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
