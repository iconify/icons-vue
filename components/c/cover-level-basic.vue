<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xyp6wx9xg"/><path class="jej6c2f3q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cover-level-basic" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jej6c2f3q {
  d: path("M12 9za1.75 1.75 0 0 1 1.75 1.75v8.5A1.75 1.75 0 0 1 12 21a1.75 1.75 0 0 1-1.75-1.75v-8.5A1.75 1.75 0 0 1 12 9m6.25-6zA1.75 1.75 0 0 1 20 4.75v14.5A1.75 1.75 0 0 1 18.25 21a1.75 1.75 0 0 1-1.75-1.75V4.75A1.75 1.75 0 0 1 18.25 3");
}

.xyp6wx9xg {
  fill: currentColor;
  d: path("M5.75 15za1.75 1.75 0 0 1 1.75 1.75v2.5A1.75 1.75 0 0 1 5.75 21A1.75 1.75 0 0 1 4 19.25v-2.5A1.75 1.75 0 0 1 5.75 15");
}

</style>
