<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vdupljb8q"/><path class="tllg3ebgi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:child-allergy" /></template>
<style>
.tllg3ebgi {
  d: path("M7.5 8.5c0-3.5 6-3.5 6 0m-4 3.75c-1.5-1-3 0-3 1.75c0 2 1.5 3.75 3 3c1.5.75 3-1 3-3c0-1.75-1.5-2.75-3-1.75Zm0 0L10 11m8 3l4 7.5h-8Zm0 3.25v1M18 20h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vdupljb8q {
  d: path("M11.928 19.5H3.5q-.098 0-.195-.019t-.188-.057t-.173-.093t-.151-.124t-.124-.151t-.093-.173t-.057-.188T2.5 18.5v-9q0-.098.019-.195t.057-.188t.093-.173q.054-.081.124-.151t.151-.124q.082-.055.173-.093t.188-.057T3.5 8.5h14q.104 0 .206.022");
}

</style>
