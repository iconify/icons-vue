<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="etq9du57q"/><path class="dbvhpcc_p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cup-name-label" /></template>
<style>
.dbvhpcc_p {
  d: path("M9 10h6v5H9Z");
}

.etq9du57q {
  d: path("M4 3h16v3.5H4Zm1 3.5L7 21h10l2-14.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
