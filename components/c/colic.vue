<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fcp9wabvo"/><path class="b6ivw5b2a"/><path class="nbuw36b-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:colic" /></template>
<style>
.b6ivw5b2a {
  d: path("M11.25 3.5c-.5-1.25 1.25-1.5 1.5-.5M7.5 9l2 1l-2 1m9-2l-2 1l2 1");
}

.fcp9wabvo {
  d: path("M3 12.5a9 9 0 1 0 18 0a9 9 0 1 0-18 0Z");
}

.nbuw36b-c {
  fill: currentColor;
  d: path("M9.75 16a2.25 2.5 0 1 0 4.5 0a2.25 2.5 0 1 0-4.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
