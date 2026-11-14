<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lqxk94b9h"/><path class="scys8ib0p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:code-diff-split" /></template>
<style>
.lqxk94b9h {
  d: path("M4.5 2.5h3l3 3v14a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2v-15a2 2 0 0 1 2-2Zm11 0h3l3 3v14a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2v-15a2 2 0 0 1 2-2Z");
}

.scys8ib0p {
  d: path("M7.5 2.5v3h3m8-3v3h3M5.25 11h2.5m-2.5 4h2.5m8.5-4h2.5m-2.5 4h2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
