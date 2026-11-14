<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kxz67hdcx"/><path class="r6mf3scok"/><path class="j52mq0f-t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:directional-drilling" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j52mq0f-t {
  fill: currentColor;
  d: path("m19.5 16.75l.117.098a1.5 1.5 0 0 1 0 2.304l-.117.098a.915.915 0 0 1-1.5-.703v-1.094a.915.915 0 0 1 1.5-.703");
}

.kxz67hdcx {
  d: path("M2 3.5h8m-4 0V14a4 4 0 0 0 4 4h6");
}

.r6mf3scok {
  d: path("M16.75 15.5zA1.25 1.25 0 0 1 18 16.75v2.5a1.25 1.25 0 0 1-1.25 1.25a1.25 1.25 0 0 1-1.25-1.25v-2.5a1.25 1.25 0 0 1 1.25-1.25");
}

</style>
