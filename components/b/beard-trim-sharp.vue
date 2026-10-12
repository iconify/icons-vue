<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="xzz6ztbgs"/><path class="stt4mxbms"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:beard-trim-sharp" /></template>
<style>
.stt4mxbms {
  d: path("M8 14.25h2.125L12 12.75l1.875 1.5H16c-1 1.5-2.5 2-4 1.25c-1.5.75-3 .25-4-1.25Zm2.25 4h3.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xzz6ztbgs {
  d: path("M4.25 7v4.5c0 5.5 3.5 9.75 7.75 9.75s7.75-4.25 7.75-9.75V7q-1.5 4.5-4.5 4.5h-6.5q-3 0-4.5-4.5Z");
}

</style>
