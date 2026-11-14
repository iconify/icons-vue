<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y4tip2brg"/><path class="l5gypzilh"/><path class="cf6mjrbtj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:income-tax-refund" /></template>
<style>
.cf6mjrbtj {
  d: path("m9.5 17.5l-2.25 2.25L9.5 22");
}

.l5gypzilh {
  d: path("M9.5 8.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM17 14v3.5a2.25 2.25 0 0 1-2.25 2.25h-7.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y4tip2brg {
  d: path("M2.5 3.5h19V14h-19Z");
}

</style>
