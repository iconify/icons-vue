<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqzd2ljkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fleece-jacket" /></template>
<style>
.wqzd2ljkj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 3h7v3.5M8.5 3v3.5m0 0l-3 1a3 3 0 0 0-2.5 3V21h18V10.5a3 3 0 0 0-2.5-3l-3-1M12 3v18m-5.5-7.5V21m11-7.5V21");
}

</style>
