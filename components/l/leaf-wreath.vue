<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tmyes5nuj"/><path class="py10o1aaa"/><path class="zl1hr1bri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leaf-wreath" /></template>
<style>
.py10o1aaa {
  d: path("M9.75 19a6.5 6.5 0 0 0 6.5-11M7 17.25l-4.25-2.5Q3 19.5 7 17.25ZM5.5 12.5L4.25 7.75Q1.5 11 5.5 12.5ZM7.75 8l2.5-4.25Q6 4.25 7.75 8Z");
}

.tmyes5nuj {
  d: path("M14.25 19a6.5 6.5 0 0 1-6.5-11");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zl1hr1bri {
  d: path("m17 17.25l4.25-2.5Q21 19.5 17 17.25Zm1.5-4.75l1.25-4.75Q22.5 11 18.5 12.5ZM16.25 8l-2.5-4.25q4.25.5 2.5 4.25Z");
}

</style>
