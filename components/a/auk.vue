<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zh_iu5qqb"/><path class="p5guyrbaj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:auk" /></template>
<style>
.p5guyrbaj {
  d: path("M10.5 10.5c1.25 2 1.25 4.5-.25 6.25M14 4.5c1.75 0 3 .5 3.5 1.25l-3.5.5Zm-3.75 15v2h2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zh_iu5qqb {
  d: path("M14 4.5c-.5-1.1-1.5-1.75-2.75-1.75c-1.75 0-3 1.25-3 3c0 2.25-2 4.25-2 8.25c0 3.5 1.5 5.5 4 5.5c2.75 0 4.25-2 4.25-5.5c0-3-1.75-4.5-1.5-6.25c.25-.5.75-1 1-1.5Zm-3 1h.01");
}

</style>
