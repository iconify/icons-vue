<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w3eo267ca"/><path class="de4_krqzo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:compliance-shield" /></template>
<style>
.de4_krqzo {
  d: path("M8.75 12.25L11 14.5l4.25-4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w3eo267ca {
  d: path("m12 2.75l6.6 2.45a1 1 0 0 1 .65.94v5.26c0 4.4-2.9 7.6-7.25 9.85C7.65 19 4.75 15.8 4.75 11.4V6.14a1 1 0 0 1 .65-.94Zm-3.25 5h6.5");
}

</style>
