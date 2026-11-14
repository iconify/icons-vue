<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rxttv0b2y"/><path class="wed047bha"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:billing-tax-id" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rxttv0b2y {
  d: path("M11.678 21H3.5V2.5H12L17.5 8v3.722");
}

.wed047bha {
  d: path("M12 2.5V8h5.5m-11 3H13m-6.5 4h4m6.5-.5l-.75 7m4-7l-.75 7m-5-4.75h7M14 19.5h7");
}

</style>
