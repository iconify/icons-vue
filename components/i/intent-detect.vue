<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xwx-3_b6l"/><path class="khr5dib5h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:intent-detect" /></template>
<style>
.khr5dib5h {
  d: path("M8 10.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm4 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xwx-3_b6l {
  d: path("M6 3.5h12A2.5 2.5 0 0 1 20.5 6v9a2.5 2.5 0 0 1-2.5 2.5h-8L6 21v-3.5A2.5 2.5 0 0 1 3.5 15V6A2.5 2.5 0 0 1 6 3.5Z");
}

</style>
