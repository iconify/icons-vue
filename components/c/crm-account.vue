<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v5vgenb3a"/><path class="var4abmhl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crm-account" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v5vgenb3a {
  d: path("M2.5 6a2 2 0 0 1 2-2H9l2 2h8.5a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2Z");
}

.var4abmhl {
  d: path("M10 10.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM8 20a4 3.5 0 0 1 8 0");
}

</style>
