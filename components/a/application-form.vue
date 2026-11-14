<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qh2tmnben"/><path class="cqxeqmbgj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:application-form" /></template>
<style>
.cqxeqmbgj {
  d: path("m19.743 8.654l.353.353a1.5 1.5 0 0 1 0 2.122l-5.676 5.676a1.5 1.5 0 0 1-.8.416l-1.037.183a1.068 1.068 0 0 1-1.237-1.237l.183-1.037a1.5 1.5 0 0 1 .416-.8l5.676-5.676a1.5 1.5 0 0 1 2.122 0M6.5 6.5h7m-7 3.5h5.25M6.5 13.5H8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qh2tmnben {
  d: path("M16.5 5.75V4.5a2 2 0 0 0-2-2h-9a2 2 0 0 0-2 2v15a2 2 0 0 0 2 2h9a2 2 0 0 0 2-2v-.75");
}

</style>
