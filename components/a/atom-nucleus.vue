<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aeq7ij32i"/><path class="pj4v1-t6a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:atom-nucleus" /></template>
<style>
.aeq7ij32i {
  d: path("M7.5 8.25a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Z");
}

.pj4v1-t6a {
  d: path("M3 16a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Zm9 0a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
