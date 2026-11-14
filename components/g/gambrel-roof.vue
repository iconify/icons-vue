<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cn-mhh-eh"/><path class="of9ovze_b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gambrel-roof" /></template>
<style>
.cn-mhh-eh {
  d: path("M3.5 18.75v-7.265a1.75 1.75 0 0 1 .249-.901L6.22 6.467a1.75 1.75 0 0 1 .776-.692l4.28-1.946a1.75 1.75 0 0 1 1.448 0l4.28 1.946a1.75 1.75 0 0 1 .776.692l2.471 4.117a1.75 1.75 0 0 1 .249.901v7.265a1.75 1.75 0 0 1-1.75 1.75H5.25a1.75 1.75 0 0 1-1.75-1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.of9ovze_b {
  d: path("M9 20.5v-6h6v6m-6-6l6 6m0-6l-6 6");
}

</style>
