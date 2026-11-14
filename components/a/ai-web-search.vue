<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z81slaclh"/><path class="qkii7vicd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ai-web-search" /></template>
<style>
.qkii7vicd {
  d: path("M7.5 10.5a3 7 0 1 0 6 0a3 7 0 1 0-6 0Zm-4 0h14m-2 5l5 5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z81slaclh {
  d: path("M3.5 10.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0Z");
}

</style>
