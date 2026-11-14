<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qpxulrj8s"/><path class="isw25bqat"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:concrete-pour" /></template>
<style>
.isw25bqat {
  d: path("M12.75 6.5C16 8 17 11 17 15.5h-3.25c0-2-1-4-2.75-4.5ZM2.5 18.5h19v3h-19Z");
}

.qpxulrj8s {
  d: path("m13.486 4.408l-6.92-1.454l-1.71 4.698l6.236 3.334");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
