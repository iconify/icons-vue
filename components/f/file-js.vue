<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jz9wy2bsc"/><path class="n5tk9jbev"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-js" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jz9wy2bsc {
  d: path("M13.75 2.75h-6.5a2.5 2.5 0 0 0-2.5 2.5v13.5a2.5 2.5 0 0 0 2.5 2.5h9.5a2.5 2.5 0 0 0 2.5-2.5V8.25Z");
}

.n5tk9jbev {
  d: path("M13.75 2.75v3.5a2 2 0 0 0 2 2h3.5m-9 2.75v5.5a1.5 1.5 0 0 1-2.75.85m8.75-5.6a1.75 1.75 0 0 0-1.5-.75a1.6 1.6 0 0 0-.25 3.2l.5.1a1.6 1.6 0 0 1-.25 3.2a1.75 1.75 0 0 1-1.5-.75");
}

</style>
