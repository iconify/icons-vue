<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n6ii4ibmx"/><path class="nzig1s7jb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dump-bin" /></template>
<style>
.n6ii4ibmx {
  d: path("M2.5 12h19l-2 9.5h-15ZM8 12l.5 9.5M12 12v9.5m4-9.5l-.5 9.5M3.25 16.75h17.5M3.5 7.5H8V12H3.5Z");
}

.nzig1s7jb {
  d: path("M8.5 9.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm7-2.75H19V12h-3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
