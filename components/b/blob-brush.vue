<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="azjk1jbaa"/><path class="hgu-e9b9s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blob-brush" /></template>
<style>
.azjk1jbaa {
  d: path("M20.5 3.5L15 9m-1.677-1.505l3.182 3.182l-2.828 2.828l-3.182-3.182Z");
}

.hgu-e9b9s {
  d: path("M10.5 10.25c-3 1.5-5.5 5.25-7 10.25c5-1.5 8.75-4 10.25-7ZM16 17c0-2 2.5-2.5 4-1.5c2 1 2 3.75.5 5.25c-1.5 1.25-4 1-4.5-1c-.25-1 0-2 0-2.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
