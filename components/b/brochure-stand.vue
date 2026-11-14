<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mithu8bco"/><path class="txw3m9l1g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:brochure-stand" /></template>
<style>
.mithu8bco {
  d: path("M4.5 3v18.5M19.5 3v18.5m-17 0h4m11 0h4M4.5 7L6 10.5h12L19.5 7m-15 9L6 19.5h12l1.5-3.5");
}

.txw3m9l1g {
  d: path("M7.5 8V3.5h9V8m-9 9v-3.5h9V17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
