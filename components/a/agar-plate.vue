<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hbuvhnbrh"/><path class="j6xzs2bsb"/><path class="hlqdb717d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:agar-plate" /></template>
<style>
.hbuvhnbrh {
  d: path("M2.5 9.5a9.5 5.5 0 1 0 19 0a9.5 5.5 0 1 0-19 0Z");
}

.hlqdb717d {
  d: path("M5 10a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5.5-2a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5.5 2a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.j6xzs2bsb {
  d: path("M2.5 9.5v4a9.5 5.5 0 0 0 19 0v-4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
