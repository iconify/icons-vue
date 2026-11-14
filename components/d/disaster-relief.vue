<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ltefg0byz"/><path class="fg2iajxue"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:disaster-relief" /></template>
<style>
.fg2iajxue {
  d: path("m18 21l-2.75-3A2 2 0 1 1 18 15.75A2 2 0 1 1 20.75 18Z");
}

.ltefg0byz {
  d: path("M2.5 4h18v4.5h-18Zm11.75 17H3.75V8.5h15.5v2.9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
