<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lrh5jc-6c"/><path class="j208-7b0m"/><path class="v_xvn4b0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:file-stack" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j208-7b0m {
  d: path("M6 18V7a2 2 0 0 1 2-2h5.5");
}

.lrh5jc-6c {
  d: path("M11 7.5h4.5l4 4v8a2 2 0 0 1-2 2H11a2 2 0 0 1-2-2v-10a2 2 0 0 1 2-2");
}

.v_xvn4b0c {
  d: path("M3 15V4.5a2 2 0 0 1 2-2h5.5m5 5V10a1.5 1.5 0 0 0 1.5 1.5h2.5");
}

</style>
