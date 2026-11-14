<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qugwhrmuk"/><path class="su1urnbta"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cylinder" /></template>
<style>
.qugwhrmuk {
  d: path("M4.5 6a7.5 3 0 1 0 15 0a7.5 3 0 1 0-15 0Z");
}

.su1urnbta {
  d: path("M4.5 6v12a7.5 3 0 0 0 15 0V6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
