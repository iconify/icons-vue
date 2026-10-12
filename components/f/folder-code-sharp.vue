<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dy059y5wf"/><path class="r2ew8ibqj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:folder-code-sharp" /></template>
<style>
.dy059y5wf {
  d: path("M2.75 7.25v-2.5h7.1l.6.8L11.55 7l.6.8h9.1v11.45H2.75v-2.5Zm0 3.5h18.5");
}

.r2ew8ibqj {
  d: path("M9.5 12.75L7.5 15l2 2.25m5-4.5l2 2.25l-2 2.25m-1.75-5l-1.5 5.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
