<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wizf-ubov"/><path class="z0entdbcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:headset-stand" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wizf-ubov {
  d: path("M4.5 10.5a7.5 7.5 0 0 1 15 0m-17 0h4v7h-4Zm15 0h4v7h-4Z");
}

.z0entdbcr {
  d: path("M8.75 7.25a4.75 4.75 0 0 1 6.5 0M12 5.75V21m-4.5 0h9");
}

</style>
