<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ejup8vbhm"/><path class="wlkijwbcu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bat" /></template>
<style>
.ejup8vbhm {
  d: path("m12 8.5l1.25-2.25l.75 2.5c2.25-1.5 5.25-1.75 7.25-.25c-1 .75-1.5 2-1.25 3.5c-1.25-.75-2.75-.5-3.5.5c-.75-.75-2-.5-2.5.5c-.5 1.25-1.25 2.5-2 3.5c-.75-1-1.5-2.25-2-3.5c-.5-1-1.75-1.25-2.5-.5c-.75-1-2.25-1.25-3.5-.5c.25-1.5-.25-2.75-1.25-3.5c2-1.5 5-1.25 7.25.25l.75-2.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wlkijwbcu {
  d: path("M10.75 11a1.25 2.25 0 1 0 2.5 0a1.25 2.25 0 1 0-2.5 0");
}

</style>
