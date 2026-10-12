<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="brbzwyw0e"/><path class="z_9bqgbqi"/><path class="r16qawbpi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bladder" /></template>
<style>
.brbzwyw0e {
  d: path("M7 8.25C5.5 6.75 5 5 5.25 2.75M17 8.25c1.5-1.5 2-3.25 1.75-5.5M12 20v1.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r16qawbpi {
  d: path("M7.75 14h8.5c-.5 2.25-2 3.5-4.25 3.5S8.25 16.25 7.75 14");
}

.z_9bqgbqi {
  d: path("M12 6.75c4 0 7 2.75 7 6.5c0 4-3 6.75-7 6.75s-7-2.75-7-6.75c0-3.75 3-6.5 7-6.5");
}

</style>
