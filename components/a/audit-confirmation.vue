<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nd1hx00er"/><path class="jjt2jlbxz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:audit-confirmation" /></template>
<style>
.jjt2jlbxz {
  d: path("m3.5 6.5l8.5 6l8.5-6M14.25 18L18 14.5l3.75 3.5v3.75h-7.5Z");
}

.nd1hx00er {
  d: path("M11.4 19H2.5V5h19v9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
