<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="yq_mgqbbp"/><path class="gixf-bclx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chili-sharp" /></template>
<style>
.gixf-bclx {
  d: path("m15.75 7.25l-.433-3.033L18.25 2.75m-2 8l-.667 2.667L13 16");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yq_mgqbbp {
  d: path("M18 7.5c1.5 1.5 1.25 4.5-.5 7c-2.5 3.5-7 6.25-12.75 6.5h-2l1.75-1.05c5.25-2.7 8-6.95 9-11.45c.4-1.75 3-2.5 4.5-1Z");
}

</style>
