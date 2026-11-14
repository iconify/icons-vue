<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hdc4j_jfs"/><path class="j7tyhbbpo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cubby-shelves" /></template>
<style>
.hdc4j_jfs {
  d: path("M3 3h18v18H3Zm9 0v18m-9-9h18");
}

.j7tyhbbpo {
  d: path("M14.5 15.75h4V21h-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
