<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zaha57b9p"/><path class="zntn76-mv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:garden-apron" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zaha57b9p {
  d: path("M8.5 7h7v4h3v8a2 2 0 0 1-2 2h-9a2 2 0 0 1-2-2v-8h3Zm1 0c0-4.5 5-4.5 5 0m-9 4l-3 2m16-2l3 2");
}

.zntn76-mv {
  d: path("M9 14.25h6V16a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2Z");
}

</style>
