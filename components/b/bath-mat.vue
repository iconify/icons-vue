<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vgtjupbng"/><path class="y7o_d111u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bath-mat" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vgtjupbng {
  d: path("M3.5 4h17a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1h-17a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1Z");
}

.y7o_d111u {
  d: path("M8 18.25c-1.25 0-2-1-1.75-2.5l.5-3c.25-1.25 1-2 2.25-2s1.75 1 1.5 2.5l-.75 3c-.25 1.25-.75 2-1.75 2Zm8-1.5c1.25 0 2-1 1.75-2.5l-.5-3c-.25-1.25-1-2-2.25-2s-1.75 1-1.5 2.5l.75 3c.25 1.25.75 2 1.75 2Zm-8.75-8.5h.01M10 8h.01m6.74-1.25h.01M14 6.5h.01");
}

</style>
