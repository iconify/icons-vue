<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p0g_xtboq"/><path class="g3cyggwvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:api-batch-request" /></template>
<style>
.g3cyggwvm {
  d: path("m8 2.25l2.5 2.5L8 7.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p0g_xtboq {
  d: path("M12.688 2.5h6.625A2.19 2.19 0 0 1 21.5 4.688v.125A2.19 2.19 0 0 1 19.313 7h-6.625A2.19 2.19 0 0 1 10.5 4.813v-.125A2.19 2.19 0 0 1 12.688 2.5m0 7.25h6.625a2.19 2.19 0 0 1 2.187 2.188v.125a2.19 2.19 0 0 1-2.187 2.187h-6.625a2.19 2.19 0 0 1-2.188-2.187v-.125a2.19 2.19 0 0 1 2.188-2.188m0 7.25h6.625a2.19 2.19 0 0 1 2.187 2.188v.125a2.19 2.19 0 0 1-2.187 2.187h-6.625a2.19 2.19 0 0 1-2.188-2.187v-.125A2.19 2.19 0 0 1 12.688 17M2.5 4.75h8");
}

</style>
