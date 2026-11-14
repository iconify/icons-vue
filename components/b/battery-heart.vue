<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lm2lq82ov"/><path class="j53nzzbxi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:battery-heart" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j53nzzbxi {
  d: path("m12.75 9l-2 3.5h2.5l-2 3");
}

.lm2lq82ov {
  d: path("m12 20l-7-7a4.5 4.5 0 0 1 5.5-6.5v-2h3v2A4.5 4.5 0 0 1 19 13Z");
}

</style>
