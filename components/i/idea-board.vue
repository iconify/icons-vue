<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="riwf9bihd"/><path class="nn8bz70tv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:idea-board" /></template>
<style>
.nn8bz70tv {
  d: path("M21 15h-4a2 2 0 0 0-2 2v4m-6.25-7.25V12.5a3.75 3.75 0 1 1 4.5 0v1.25Zm.5 2.75h3.5");
}

.riwf9bihd {
  d: path("M5 3h14a2 2 0 0 1 2 2v10l-6 6H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
