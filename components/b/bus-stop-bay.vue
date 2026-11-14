<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s-b3xv35b"/><path class="senu2xipu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bus-stop-bay" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s-b3xv35b {
  d: path("M3 14V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v9Zm0-6h18");
}

.senu2xipu {
  d: path("M6.5 16a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-11 2.5h2V21h15v-2.5h2");
}

</style>
