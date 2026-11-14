<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rdnikjbgl"/><path class="ewb430v3s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dark-sky" /></template>
<style>
.ewb430v3s {
  d: path("M3 21q9-4.5 18 0M5 4.75Q5.5 6 6.75 6.5Q5.5 7 5 8.25Q4.5 7 3.25 6.5Q4.5 6 5 4.75Zm14 0Q19.5 6 20.75 6.5Q19.5 7 19 8.25Q18.5 7 17.25 6.5Q18.5 6 19 4.75ZM12 3q.25 1.25 1.5 1.5q-1.25.25-1.5 1.5q-.25-1.25-1.5-1.5Q11.75 4.25 12 3Z");
}

.rdnikjbgl {
  d: path("M6.5 19.5v-5a5.5 5.5 0 0 1 4-5.25v4.25h3V9.25a5.5 5.5 0 0 1 4 5.25v5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
