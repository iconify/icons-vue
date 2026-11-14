<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ej8no5byx"/><path class="hsxcruxal"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dryer-sheet" /></template>
<style>
.ej8no5byx {
  d: path("M5 4q3.5-1.5 7 0t7 0v16q-3.5 1.5-7 0t-7 0Z");
}

.hsxcruxal {
  d: path("M8.5 12q1.75-1.25 3.5 0t3.5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
