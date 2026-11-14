<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b-m78xnig"/><path class="zprq61b6i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:agile-epic" /></template>
<style>
.b-m78xnig {
  d: path("M14.5 2.5L4.5 14h7l-2 7.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zprq61b6i {
  d: path("m9.5 21.5l10-11.5h-7l2-7.5");
}

</style>
