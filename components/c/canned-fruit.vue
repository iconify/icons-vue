<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wuqjp03eq"/><path class="jf4uqjblp"/><path class="aj7epzvgs"/><path class="yxgzmnbzx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:canned-fruit" /></template>
<style>
.aj7epzvgs {
  d: path("M8.5 14.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jf4uqjblp {
  d: path("M5 5v14a7 2 0 0 0 14 0V5");
}

.wuqjp03eq {
  d: path("M5 5a7 2 0 1 0 14 0A7 2 0 1 0 5 5");
}

.yxgzmnbzx {
  d: path("M12 11q-1.5 2.5-.5 5m.5-5q1.25-1.75 3-1q-1.25 1.75-3 1");
}

</style>
