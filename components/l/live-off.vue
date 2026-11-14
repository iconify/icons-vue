<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q83339b9q"/><path class="o9f_46jto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:live-off" /></template>
<style>
.o9f_46jto {
  d: path("M9.348 14.652q-.245-.245-.441-.53q-.195-.285-.336-.602q-.14-.316-.22-.653t-.097-.682m6.398-2.837q.245.245.441.53q.195.285.336.602q.14.316.22.653t.097.682M3.5 3.5l17 17");
}

.q83339b9q {
  d: path("M8.4 4.5h12.1q.098 0 .195.019t.188.057t.173.093q.081.054.151.124t.124.151q.055.082.093.173t.057.188t.019.195v12.086M15.528 19.5H3.5q-.098 0-.195-.019t-.188-.057t-.173-.093t-.151-.124t-.124-.151t-.093-.173t-.057-.188T2.5 18.5V6.443");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
