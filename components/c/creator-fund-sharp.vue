<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ez4rmuw2t"/><path class="rdawnyb-w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:creator-fund-sharp" /></template>
<style>
.ez4rmuw2t {
  d: path("M7.5 3.5h9M4.25 6.75h15.5v14.5H4.25z");
}

.rdawnyb-w {
  d: path("m12.14 10.57l.82 1.84l.15.32l.34.04l2.01.21l.34.03l-.26.24l-1.49 1.35l-.26.23l.07.34l.42 1.97l.07.35l-.3-.18l-1.75-1.01l-.3-.17l-.3.17l-1.75 1.01l-.3.18l.07-.35l.42-1.97l.07-.34l-.26-.23l-1.49-1.35l-.26-.24l.34-.03l2.01-.21l.34-.04l.15-.32l.82-1.84l.14-.32z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
