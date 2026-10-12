<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="zh928oeob"/><path class="ndlitxn8q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:inspection" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ndlitxn8q {
  d: path("M8.5 5.25v-1.5a1 1 0 0 1 1-1h5a1 1 0 0 1 1 1v1.5ZM7.5 10l1 1l2-2m2 1h4m-9 4l1 1l2-2m2 1h4m-8.75 3l2 2m0-2l-2 2m4.75-1h4");
}

.zh928oeob {
  width: 15.5px;
  height: 16px;
  x: 4.25px;
  y: 5.25px;
  rx: 1.75px;
}

</style>
