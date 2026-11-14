<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bd-35ibop"/><path class="fy2t748il"/><path class="pckj6wzkj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:balloon-animal" /></template>
<style>
.bd-35ibop {
  d: path("M5.75 13a4.75 2.25 0 1 0 9.5 0a4.75 2.25 0 1 0-9.5 0Z");
}

.fy2t748il {
  d: path("M14.25 9.25a1.75 3 0 1 0 3.5 0a1.75 3 0 1 0-3.5 0Z");
}

.pckj6wzkj {
  d: path("M15.75 5.25a3 1.75 0 1 0 6 0a3 1.75 0 1 0-6 0ZM6.5 17.75a1.25 2.75 0 1 0 2.5 0a1.25 2.75 0 1 0-2.5 0Zm5.5 0a1.25 2.75 0 1 0 2.5 0a1.25 2.75 0 1 0-2.5 0Zm-8.5-7.5a1 2 0 1 0 2 0a1 2 0 1 0-2 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
