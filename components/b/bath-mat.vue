<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zuy18rxxe"/><path class="fh1uxjb9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bath-mat" /></template>
<style>
.fh1uxjb9f {
  d: path("M8 18.25c-1.25 0-2-1-1.75-2.5l.5-3c.25-1.25 1-2 2.25-2s1.75 1 1.5 2.5l-.75 3c-.25 1.25-.75 2-1.75 2m8-1.5c1.25 0 2-1 1.75-2.5l-.5-3c-.25-1.25-1-2-2.25-2s-1.75 1-1.5 2.5l.75 3c.25 1.25.75 2 1.75 2m-8.75-8.5h.01M10 8h.01m6.74-1.25h.01M14 6.5h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zuy18rxxe {
  d: path("M7.75 4h8.5a5.25 5.25 0 0 1 5.25 5.25v5.5A5.25 5.25 0 0 1 16.25 20h-8.5a5.25 5.25 0 0 1-5.25-5.25v-5.5A5.25 5.25 0 0 1 7.75 4");
}

</style>
