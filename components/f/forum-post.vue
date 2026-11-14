<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ehxvtbbcf"/><path class="mg5xadb2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:forum-post" /></template>
<style>
.ehxvtbbcf {
  d: path("M4.5 7h10a2 2 0 0 1 2 2v7a2 2 0 0 1-2 2h-6L5 21v-3h-.5a2 2 0 0 1-2-2V9a2 2 0 0 1 2-2Z");
}

.mg5xadb2e {
  d: path("M8.5 7V5a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v7a2 2 0 0 1-2 2h-3M6 11h7m-7 3.5h4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
