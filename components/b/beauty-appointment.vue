<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zsn13c4wd"/><path class="b3x1yvboz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:beauty-appointment" /></template>
<style>
.b3x1yvboz {
  d: path("M18 14.5q.5 3 3.5 3.5q-3 .5-3.5 3.5q-.5-3-3.5-3.5q3-.5 3.5-3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zsn13c4wd {
  d: path("M14.7 21H3.5V4.5h17V14M8 2.5v4m8-4v4m-12.5 3h17M8 13.5h.01m3.99 0h.01M8 17.5h.01");
}

</style>
