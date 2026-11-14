<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hq853achm"/><path class="e8cjyuwei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baby-penguin" /></template>
<style>
.e8cjyuwei {
  d: path("M12 9c1-1.25 3.25-1.25 3.25 1v4c0 2.25-1.5 3.5-3.25 3.5S8.75 16.25 8.75 14v-4C8.75 7.75 11 7.75 12 9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hq853achm {
  d: path("M12 3.5c4.25 0 6.5 3.5 6.5 8V14c0 4-2.75 6.5-6.5 6.5S5.5 18 5.5 14v-2.5c0-4.5 2.25-8 6.5-8m-6.5 8l-2 3.5m15-3.5l2 3.5");
}

</style>
