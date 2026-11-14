<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hg_qa-8dv"/><path class="rhmo8vbfx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:caravan-dealer" /></template>
<style>
.hg_qa-8dv {
  d: path("M2.5 16.5V8A2.5 2.5 0 0 1 5 5.5h7.5A2.5 2.5 0 0 1 15 8v8.5Z");
}

.rhmo8vbfx {
  d: path("M5.5 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm9.5-12l6.5 3v11m-16-12h4v3h-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
