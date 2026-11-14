<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ed8qtsb7t"/><path class="rjwjeqf_f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:farm-cooperative" /></template>
<style>
.ed8qtsb7t {
  d: path("M10.264 20.5H2.5V10l2.75-4.5l6-3l6 3L20 10v1.936");
}

.rjwjeqf_f {
  d: path("M9.25 7.5h4v4h-4Zm4 8.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM13 21.5a1.75 1.75 0 0 1 3.5 0m1.5 0a1.75 1.75 0 0 1 3.5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
