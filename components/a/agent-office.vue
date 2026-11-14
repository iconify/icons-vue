<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nbyf0gz5s"/><path class="pglw4jure"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:agent-office" /></template>
<style>
.nbyf0gz5s {
  d: path("M3.5 3h17v18.5h-17Z");
}

.pglw4jure {
  d: path("M6.25 6.5H8.5v2.25H6.25Zm4.5 0h2.5v2.25h-2.5Zm4.75 0h2.25v2.25H15.5Zm-5.5 15v-6h4v6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
