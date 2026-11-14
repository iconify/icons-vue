<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g_82bym8k"/><path class="q2lca82dq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cross-tab" /></template>
<style>
.g_82bym8k {
  fill: currentColor;
  d: path("M3 5.5A2.5 2.5 0 0 1 5.5 3h13A2.5 2.5 0 0 1 21 5.5V8H8v13H5.5A2.5 2.5 0 0 1 3 18.5Z");
}

.q2lca82dq {
  d: path("M21 8v10.5a2.5 2.5 0 0 1-2.5 2.5H8m6.5-13v13M8 14.5h13");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
