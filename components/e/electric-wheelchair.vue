<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rs5t57lit"/><path class="obpa3n2qe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:electric-wheelchair" /></template>
<style>
.obpa3n2qe {
  d: path("M6 3.5v8h7.5l3 6h4m-2.25 3a.25.25 0 1 0 .5 0a.25.25 0 1 0-.5 0ZM8.5 14l-1 2.5H9L8 19");
}

.rs5t57lit {
  d: path("M3.5 16.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
