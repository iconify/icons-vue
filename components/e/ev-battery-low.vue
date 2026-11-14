<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tya7042sq"/><path class="kss3jsbfp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ev-battery-low" /></template>
<style>
.kss3jsbfp {
  d: path("M4.25 12a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm11 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM15 17h4.5a1 1 0 0 1 1 1v.5h1V20h-1v.5a1 1 0 0 1-1 1H15a1 1 0 0 1-1-1V18a1 1 0 0 1 1-1Zm1.25 2.25h.01");
}

.tya7042sq {
  d: path("M4.25 12H2.5V8L5 7l2.5-4h7L18 7l3.5 1v4h-1.75m-11 0h6.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
