<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jtysqlb4y"/><path class="glvk9ccgi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:golf-scorecard" /></template>
<style>
.glvk9ccgi {
  d: path("m9.904 6.527l.596.223a.801.801 0 0 1 0 1.5l-.596.223A1.04 1.04 0 0 1 8.5 7.5a1.04 1.04 0 0 1 1.404-.973M8.5 15h7m-7 3.5h7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jtysqlb4y {
  d: path("M8 2.5h8A3.5 3.5 0 0 1 19.5 6v12a3.5 3.5 0 0 1-3.5 3.5H8A3.5 3.5 0 0 1 4.5 18V6A3.5 3.5 0 0 1 8 2.5M8.5 6v5.5");
}

</style>
