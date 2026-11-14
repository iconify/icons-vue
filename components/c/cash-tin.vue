<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qqndmibhl"/><path class="qjs7vabiu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cash-tin" /></template>
<style>
.qjs7vabiu {
  d: path("M10.75 16a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0ZM12 17.25v1.5");
}

.qqndmibhl {
  d: path("M2.5 7.5h19V12h-19Zm1 4.5v8A1.5 1.5 0 0 0 5 21.5h14a1.5 1.5 0 0 0 1.5-1.5v-8M9 7.5v-2a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
