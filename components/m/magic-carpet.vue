<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yten-pbzd"/><path class="cf_4npb3r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:magic-carpet" /></template>
<style>
.cf_4npb3r {
  d: path("M8.678 11.791L6.987 8.166l7.251-3.381l1.69 3.625");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yten-pbzd {
  d: path("m4.599 13.693l12.235-5.706M6.712 18.224l12.236-5.705m-3.323-1.209a2.5 2.5 0 0 1 4.532-2.114M3.156 15.958a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m2.5 0h.01");
}

</style>
