<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hlzpxe_kj"/><path class="qpwueab6z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:eye-dollar" /></template>
<style>
.hlzpxe_kj {
  d: path("M2.5 9.75C4 6.5 6.6 4.5 9.75 4.5s5.75 2 7.25 5.25C15.5 13 12.9 15 9.75 15S4 13 2.5 9.75Z");
}

.qpwueab6z {
  d: path("M7.25 9.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm13 6.25c-.25-.6-1.05-1-2.25-1c-1.25 0-2.25.6-2.25 1.5c0 2 4.5 1 4.5 3c0 .9-1 1.5-2.25 1.5c-1.2 0-2-.4-2.25-1M18 13.75V15m0 6v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
