<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o0uxpabcc"/><path class="owrp88rnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bash-script" /></template>
<style>
.o0uxpabcc {
  d: path("M2.5 3.5h19v17h-19Z");
}

.owrp88rnz {
  d: path("M10.5 9.5C10.25 8.25 9.25 7.75 8 7.75c-1.5 0-2.5.75-2.5 2c0 2.5 5 1.75 5 4.5c0 1.25-1 2-2.5 2c-1.25 0-2.25-.5-2.5-1.5M8 6.25v11.5m5.5-1.25H18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
