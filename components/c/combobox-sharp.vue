<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ssngo0btg"/><path class="a41ar10ql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:combobox-sharp" /></template>
<style>
.a41ar10ql {
  d: path("m14.75 11l2 2l2-2");
}

.ssngo0btg {
  d: path("M2.75 7h18.5v10H2.75zm3.5 5h6.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
