<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vqst2rb_x"/><path class="zrsirmbtd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baby-development" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vqst2rb_x {
  d: path("M5.625 12.5h3.25a2.625 2.625 0 0 1 2.625 2.625v3.25A2.625 2.625 0 0 1 8.875 21h-3.25A2.625 2.625 0 0 1 3 18.375v-3.25A2.625 2.625 0 0 1 5.625 12.5m9.5 0h3.25A2.625 2.625 0 0 1 21 15.125v3.25A2.625 2.625 0 0 1 18.375 21h-3.25a2.625 2.625 0 0 1-2.625-2.625v-3.25a2.625 2.625 0 0 1 2.625-2.625M10.375 3h3.25a2.625 2.625 0 0 1 2.625 2.625v3.25a2.625 2.625 0 0 1-2.625 2.625h-3.25A2.625 2.625 0 0 1 7.75 8.875v-3.25A2.625 2.625 0 0 1 10.375 3");
}

.zrsirmbtd {
  d: path("m5.5 19l1.75-4.25L9 19m5.75-2.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0M12 5.5v3");
}

</style>
