<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w8y098k2m"/><path class="m0s1iicze"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ab-test" /></template>
<style>
.m0s1iicze {
  d: path("m4.5 15l2.25-6L9 15m-3.75-2h3m7.25-4v6m0-6h2.25a1.5 1.5 0 0 1 0 3H15.5m0 0H18a1.5 1.5 0 0 1 0 3h-2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w8y098k2m {
  d: path("M2.5 4.5H11v15H2.5Zm10.5 0h8.5v15H13Z");
}

</style>
