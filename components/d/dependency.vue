<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zqnxeac8q"/><path class="p_dm2tzcb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dependency" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p_dm2tzcb {
  d: path("m10 16l2 2l-2 2");
}

.zqnxeac8q {
  d: path("M5.125 3h4.25A2.625 2.625 0 0 1 12 5.625v.75A2.625 2.625 0 0 1 9.375 9h-4.25A2.625 2.625 0 0 1 2.5 6.375v-.75A2.625 2.625 0 0 1 5.125 3m9.5 12h4.25a2.625 2.625 0 0 1 2.625 2.625v.75A2.625 2.625 0 0 1 18.875 21h-4.25A2.625 2.625 0 0 1 12 18.375v-.75A2.625 2.625 0 0 1 14.625 15M7.25 9v9H12");
}

</style>
