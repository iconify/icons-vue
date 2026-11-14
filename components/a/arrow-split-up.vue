<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tvql_fb0l"/><path class="a2psuhk-y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:arrow-split-up" /></template>
<style>
.a2psuhk-y {
  d: path("m4 7l3-3l3 3m4 0l3-3l3 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tvql_fb0l {
  d: path("M12 20.5V15c0-3-5-3-5-6.5V4m5 11c0-3 5-3 5-6.5V4");
}

</style>
