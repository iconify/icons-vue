<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sqac3lbyh"/><path class="wfp6attlx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coffee-machine-room" /></template>
<style>
.sqac3lbyh {
  d: path("M4 3h16v5H8v10h12v3H4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wfp6attlx {
  d: path("M12.5 11h5v1.5L19 16v2h-8v-2l1.5-3.5Z");
}

</style>
