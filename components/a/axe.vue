<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qcgfb0dhz"/><path class="gibbinwgp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:axe" /></template>
<style>
.gibbinwgp {
  d: path("M16.25 6.25L14 2.75q-3.75.5-4.25 4.25L13 9.25");
}

.qcgfb0dhz {
  d: path("m16.907 5.472l2.121 2.121L5.593 21.028l-2.121-2.121Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
