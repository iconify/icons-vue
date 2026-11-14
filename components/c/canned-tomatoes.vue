<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="an7bdh8ts"/><path class="r4xl3mbcl"/><path class="iealp8bgl"/><path class="czbqpcc_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:canned-tomatoes" /></template>
<style>
.an7bdh8ts {
  d: path("M4.5 5.5a7.5 2.25 0 1 0 15 0a7.5 2.25 0 1 0-15 0");
}

.czbqpcc_w {
  d: path("M12 11.75q.5-1 2-1.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iealp8bgl {
  d: path("M8.75 15a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

.r4xl3mbcl {
  d: path("M4.5 5.5v13a7.5 2.5 0 0 0 15 0v-13");
}

</style>
