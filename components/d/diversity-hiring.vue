<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lfx0agbmq"/><path class="v5ekr8o2v"/><path class="c3wgojkty"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:diversity-hiring" /></template>
<style>
.c3wgojkty {
  d: path("M18 15v6m-3-3h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lfx0agbmq {
  d: path("M8 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0M4 21c0-4 3.5-6.5 8-6.5c1.147 0 2.23.163 3.206.471");
}

.v5ekr8o2v {
  fill: currentColor;
  d: path("M12 3.5a4 4 0 0 0 0 8Zm0 11c-4.5 0-8 2.5-8 6.5h8Z");
}

</style>
