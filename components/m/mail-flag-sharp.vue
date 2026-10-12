<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="xeahgxpeb"/><path class="o8znwbc9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mail-flag-sharp" /></template>
<style>
.o8znwbc9d {
  d: path("m4.5 10.75l2.9 2.2l.85.585l.85-.585l2.9-2.2M16.25 13V3.25h4.5L19.5 6l1.25 2.75h-4.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xeahgxpeb {
  d: path("M2.75 7.25h11v12h-11z");
}

</style>
