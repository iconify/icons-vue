<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qxocr3buf"/><path class="izzcmdlqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:journal" /></template>
<style>
.izzcmdlqz {
  d: path("M12.5 2.5V8l1.75-1.25L16 8V2.5");
}

.qxocr3buf {
  d: path("M5 2.5h14v19H5Zm3.5 0v19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
