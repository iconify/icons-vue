<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d4_1691wu"/><path class="s6_27vbbx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:address-label" /></template>
<style>
.d4_1691wu {
  d: path("M4.5 5h13l4 4v8a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2Z");
}

.s6_27vbbx {
  d: path("M7.5 15.5C5 13 5 12.5 5 11a2.5 2.5 0 0 1 5 0c0 1.5 0 2-2.5 4.5Zm5.5-5h5m-5 4h3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
