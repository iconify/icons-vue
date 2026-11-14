<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b1rmupb0u"/><path class="ovu6qstmq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:code-generator" /></template>
<style>
.b1rmupb0u {
  d: path("M13.3 19H3V2.5h13v10.8");
}

.ovu6qstmq {
  d: path("m8 8l-2.25 2.5L8 13m3-5l2.25 2.5L11 13m6.75.75q.5 3.5 4 4q-3.5.5-4 4q-.5-3.5-4-4q3.5-.5 4-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
