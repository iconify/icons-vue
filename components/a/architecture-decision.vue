<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uwivq1yig"/><path class="qpbfohcpa"/><path class="r9bfi0t7i"/><path class="f6_7j78_y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:architecture-decision" /></template>
<style>
.f6_7j78_y {
  d: path("M11 10.5v3.25L8.25 17M11 13.75L13.75 17");
}

.qpbfohcpa {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4");
}

.r9bfi0t7i {
  fill: currentColor;
  d: path("M10 10.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0ZM7.25 17a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm5.5 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uwivq1yig {
  d: path("M7 2.5h6.5l6 6V19a2.5 2.5 0 0 1-2.5 2.5H7A2.5 2.5 0 0 1 4.5 19V5A2.5 2.5 0 0 1 7 2.5Z");
}

</style>
