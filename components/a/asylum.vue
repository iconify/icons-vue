<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="avwiuvbsw"/><path class="wznx48bpa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:asylum" /></template>
<style>
.avwiuvbsw {
  d: path("m3 11l9-7l9 7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wznx48bpa {
  d: path("M9.5 11.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM7 21c0-3.25 2.25-4.75 5-4.75s5 1.5 5 4.75");
}

</style>
