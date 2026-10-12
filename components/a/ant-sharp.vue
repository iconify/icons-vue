<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="clr0mpgfa"/><path class="ctw7rsb2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ant-sharp" /></template>
<style>
.clr0mpgfa {
  cx: 12px;
  cy: 5.5px;
  r: 1.75px;
}

.ctw7rsb2k {
  d: path("M10.25 10.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM9 17.5a3 3.25 0 1 0 6 0a3 3.25 0 1 0-6 0Zm1.5-7.75L7 7.5m6.5 2.25L17 7.5m-6.75 3.75h-4m7.5 0h4m-7.5.75L6.5 14l-1 3.5m8.25-5.5l3.75 2l1 3.5M11 4L9.5 2.75M13 4l1.5-1.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
