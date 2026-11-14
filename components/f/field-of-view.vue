<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rh4hqugip"/><path class="uhmgd-eyj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:field-of-view" /></template>
<style>
.rh4hqugip {
  d: path("M2 12a10 10 0 1 0 20 0a10 10 0 1 0-20 0Z");
}

.uhmgd-eyj {
  fill: currentColor;
  d: path("M12 12L6 4a10 10 0 0 1 12 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
