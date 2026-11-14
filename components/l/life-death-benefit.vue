<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v82dfe_ny"/><path class="scgvdhw-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:life-death-benefit" /></template>
<style>
.scgvdhw-l {
  d: path("M10.5 17a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v82dfe_ny {
  d: path("m12 12.5l-5.25-5A3 3 0 0 1 12 4.25a3 3 0 0 1 5.25 3.25Zm-9.5 0h19v9h-19Z");
}

</style>
