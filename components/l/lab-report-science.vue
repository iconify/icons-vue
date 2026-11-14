<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u28ayjbia"/><path class="ks64ycbsy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lab-report-science" /></template>
<style>
.ks64ycbsy {
  d: path("m8 17.5l3-3.5l2.5 2l2.5-4");
}

.u28ayjbia {
  d: path("M5 2.5h9.5L19 7v14.5H5Zm3 5h3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
