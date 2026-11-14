<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="whzkf_vgt"/><path class="jco8odu9n"/><path class="qlynmj8ag"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bug-catcher" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jco8odu9n {
  d: path("M9.25 16.25a2.75 3.5 0 1 0 5.5 0a2.75 3.5 0 1 0-5.5 0");
}

.qlynmj8ag {
  d: path("M10.75 11.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0M7 14l2.25 1M7 18.75l2.25-1.25M17 14l-2.25 1M17 18.75l-2.25-1.25");
}

.whzkf_vgt {
  d: path("M7.25 2.5h9.5a1.75 1.75 0 0 1 1.75 1.75v.5a1.75 1.75 0 0 1-1.75 1.75h-9.5A1.75 1.75 0 0 1 5.5 4.75v-.5A1.75 1.75 0 0 1 7.25 2.5m-.75 4V8c-2 .5-3 2-3 4v7A2.5 2.5 0 0 0 6 21.5h12a2.5 2.5 0 0 0 2.5-2.5v-7c0-2-1-3.5-3-4V6.5m-5.5-2h.01");
}

</style>
