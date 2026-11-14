<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kfrxcywob"/><path class="x3mqa04pb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:card-shuffle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kfrxcywob {
  d: path("m5.349 10.239l1.223-.26a2.625 2.625 0 0 1 3.113 2.022l.988 4.646a2.625 2.625 0 0 1-2.022 3.114l-1.223.26a2.625 2.625 0 0 1-3.113-2.022l-.988-4.646a2.625 2.625 0 0 1 2.022-3.114m12.079-.26l1.223.26a2.625 2.625 0 0 1 2.022 3.114l-.988 4.646a2.625 2.625 0 0 1-3.113 2.022l-1.223-.26a2.625 2.625 0 0 1-2.022-3.114l.988-4.646a2.625 2.625 0 0 1 3.113-2.022M6 6.5a7 7 0 0 1 12 0");
}

.x3mqa04pb {
  d: path("M18.5 4L18 6.5l-2.5-.75");
}

</style>
