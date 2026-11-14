<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nritab56i"/><path class="dtt5tg88g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:few-shot" /></template>
<style>
.dtt5tg88g {
  d: path("M6 9.5v-4a2 2 0 0 1 2-2h11.5a2 2 0 0 1 2 2V15a2 2 0 0 1-2 2H18M6 15.25h6.5");
}

.nritab56i {
  d: path("M2.5 9.5H18V21H2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
