<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xyvbphscw"/><path class="ompuxlb2n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:basketball-jersey" /></template>
<style>
.ompuxlb2n {
  d: path("M9 13.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xyvbphscw {
  d: path("M7.5 2.5V5C7.5 7.5 5 8 5 10.5v10a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1v-10c0-2.5-2.5-3-2.5-5.5V2.5h-2a2.5 2.5 0 0 1-5 0Z");
}

</style>
