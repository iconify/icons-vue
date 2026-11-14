<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pxyjjbbuv"/><path class="ngghv7-hy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:accountant-calculator" /></template>
<style>
.ngghv7-hy {
  d: path("M7 5.5h8v4H7Zm1.5 8h.01m4.99 0h.01M8.5 17.75h.01m5.99 3.5c0-1.5 1.5-2.5 3.5-2.5s3.5 1 3.5 2.5c0 .25-.25.5-.5.5h-6c-.25 0-.5-.25-.5-.5Zm1.75-6a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.pxyjjbbuv {
  d: path("M11.7 21.5H4v-19h14v8.2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
