<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="iodyokm9u"/><path class="bzq43xlvx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:interior-light-sharp" /></template>
<style>
.bzq43xlvx {
  d: path("M8.75 8.25h6.5a3.25 3.25 0 0 1-6.5 0Zm3.25 6v2.5M8.25 13.5l-1.5 1.75m9-1.75l1.5 1.75");
}

.iodyokm9u {
  d: path("M2.75 20.25V13.5c0-5 4-8.75 9.25-8.75s9.25 3.75 9.25 8.75v6.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
