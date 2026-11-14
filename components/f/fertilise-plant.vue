<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwjugj70v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fertilise-plant" /></template>
<style>
.qwjugj70v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.5 7a3 3 0 1 0 5-3Zm5-3l2-1.25M8 21.5V16m0 2c0-3-2.5-4.5-5.5-4.5C2.5 16.5 5 18 8 18Zm0-2c0-2.5 1.5-4 3.5-4c0 2.5-1.5 4-3.5 4Zm6.5-4.25h.01m.74 3h.01m-.76 3h.01");
}

</style>
