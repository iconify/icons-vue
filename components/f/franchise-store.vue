<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qllr8ac5y"/><path class="jswuopbim"/><path class="rte61rghe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:franchise-store" /></template>
<style>
.jswuopbim {
  d: path("M2.5 10a2.5 2.5 0 0 0 5 0a2.5 2.5 0 0 0 5 0a2.5 2.5 0 0 0 5 0M8 21.5v-4h4v4");
}

.qllr8ac5y {
  d: path("M2.5 10L4 6.5h12l1.5 3.5M4 12.5v9h12v-9");
}

.rte61rghe {
  d: path("m7 4l1-1.5h12L21.5 6v12H19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
