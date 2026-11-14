<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hn36zgbbp"/><path class="tkb05wq3e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:face" /></template>
<style>
.hn36zgbbp {
  d: path("M4.25 12a7.75 9.5 0 1 0 15.5 0a7.75 9.5 0 1 0-15.5 0m5-2h.01m5.49 0h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tkb05wq3e {
  d: path("m12 10.5l-.75 3h1m-2.5 3h4.5");
}

</style>
