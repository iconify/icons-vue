<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c0hayn6xe"/><path class="n9qi09bqy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hourglass-start" /></template>
<style>
.c0hayn6xe {
  d: path("M7 3h10v2.5c0 2.5-2.5 5-5 6.5c2.5 1.5 5 4 5 6.5V21H7v-2.5c0-2.5 2.5-5 5-6.5c-2.5-1.5-5-4-5-6.5ZM5 3h14M5 21h14");
}

.n9qi09bqy {
  d: path("M9.5 6.5h5C14 8 13.25 9 12 9.75C10.75 9 10 8 9.5 6.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
