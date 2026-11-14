<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k9kbivbar"/><path class="hqciypbxr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cad-software" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hqciypbxr {
  d: path("M12 8.75zA1.25 1.25 0 0 1 13.25 10A1.25 1.25 0 0 1 12 11.25A1.25 1.25 0 0 1 10.75 10A1.25 1.25 0 0 1 12 8.75m0-2.25v2.25m0 2.5v2.25M7.5 10h3.25m2.5 0h3.25");
}

.k9kbivbar {
  d: path("M6 3.5h12A3.5 3.5 0 0 1 21.5 7v6a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 13V7A3.5 3.5 0 0 1 6 3.5m6 13v4m-4 0h8");
}

</style>
