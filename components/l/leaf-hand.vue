<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sozz-tbhw"/><path class="ip9_wgbok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leaf-hand" /></template>
<style>
.ip9_wgbok {
  d: path("m12.75 16.25l5.25-2.5a1.5 1.5 0 0 1 1.75 2.5l-6 4.25H2.5");
}

.sozz-tbhw {
  d: path("M9.5 10.5c0-5 2.25-7 7-7c0 5-2.25 7-7 7Zm-7 4h3l3.25-1.25h3.75a1.5 1.5 0 0 1 0 3H9.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
