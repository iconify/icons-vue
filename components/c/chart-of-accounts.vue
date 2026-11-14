<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vzkv9-b9c"/><path class="f9ie41bja"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-of-accounts" /></template>
<style>
.f9ie41bja {
  d: path("M4.75 16.5V12h14.5v4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vzkv9-b9c {
  d: path("M8.5 2.5h7v5h-7Zm-6 14H7v5H2.5Zm7.25 0h4.5v5h-4.5Zm7.25 0h4.5v5H17Zm-5-9v9");
}

</style>
