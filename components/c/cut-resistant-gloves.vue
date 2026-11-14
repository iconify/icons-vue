<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eof2h7bkt"/><path class="m9g3djaje"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cut-resistant-gloves" /></template>
<style>
.eof2h7bkt {
  d: path("M12.227 20.5H7v-6l-2.75-3c-.75-.75-.75-2.25.25-3c.75-.5 1.75-.25 2.25.5L8 10.25V5.5c0-1.75 1.25-3 3-3h3c1.75 0 3 1.25 3 3v5.673M7 17h4.7M11 2.5V9m3-6.5V9");
}

.m9g3djaje {
  d: path("M18 13.75L21.5 15v2.75C21.5 20 20 21.25 18 22c-2-.75-3.5-2-3.5-4.25V15Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
