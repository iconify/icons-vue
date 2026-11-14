<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f7d_n4dzu"/><path class="ulr3r9j3h"/><path class="un22c5vpx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lead-source-web" /></template>
<style>
.f7d_n4dzu {
  d: path("M2.5 2h19v15.5h-19ZM12 17.5V21m-4 0h8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ulr3r9j3h {
  d: path("M7.25 9.75a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0Z");
}

.un22c5vpx {
  d: path("M10 9.75a2 4.75 0 1 0 4 0a2 4.75 0 1 0-4 0Zm-2.75 0h9.5");
}

</style>
