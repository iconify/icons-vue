<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ylev0mlod"/><path class="b6vyktb3l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gas-smell-report" /></template>
<style>
.b6vyktb3l {
  d: path("M8.5 14.25h7a2.25 2.25 0 0 0 0-4.5a3.5 3.5 0 0 0-7 0a2.25 2.25 0 0 0 0 4.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ylev0mlod {
  d: path("M5 3.5h14a2 2 0 0 1 2 2V15a2 2 0 0 1-2 2h-9l-4.5 4v-4H5a2 2 0 0 1-2-2V5.5a2 2 0 0 1 2-2Z");
}

</style>
