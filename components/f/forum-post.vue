<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ikc8mlwrt"/><path class="mg5xadb2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:forum-post" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ikc8mlwrt {
  d: path("M4.5 7h10a2 2 0 0 1 2 2v7a2 2 0 0 1-2 2h-6L5 21v-3h-.5a2 2 0 0 1-2-2V9a2 2 0 0 1 2-2");
}

.mg5xadb2e {
  d: path("M8.5 7V5a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v7a2 2 0 0 1-2 2h-3M6 11h7m-7 3.5h4.5");
}

</style>
