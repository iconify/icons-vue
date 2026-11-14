<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bfq-__9qq"/><path class="ntcbepbvx"/><path class="a05h5rbtq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lighting-schedule" /></template>
<style>
.a05h5rbtq {
  d: path("M17 15.25V17l1.75 1");
}

.bfq-__9qq {
  d: path("M5.5 21.5v-13a5 5 0 0 1 5-5h3v1.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ntcbepbvx {
  d: path("M10.75 7.5a2.75 2.75 0 0 1 5.5 0ZM3 21.5h5m4.5-4.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0");
}

</style>
