<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ipof0itfh"/><path class="b-lexccac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fire-drill" /></template>
<style>
.b-lexccac {
  d: path("M12 7.5c1.5 1.5 2.5 3 2.5 4.75a2.5 2.5 0 0 1-5 0c0-1.25.75-2 1.25-2.75c.5.75 1 1 1.25 1q.375-1.5 0-3Z");
}

.ipof0itfh {
  d: path("M6 10.5a6 6 0 0 1 12 0v4l1.5 2.25c.35.5.1 1.25-.5 1.25H5c-.6 0-.85-.75-.5-1.25L6 14.5Zm6-8v2M10 21h4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
