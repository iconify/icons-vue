<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mf3fscb0g"/><path class="o4nflab0t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crossing-barrier" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mf3fscb0g {
  d: path("M7.25 11h.5a1.75 1.75 0 0 1 1.75 1.75v7a1.75 1.75 0 0 1-1.75 1.75h-.5a1.75 1.75 0 0 1-1.75-1.75v-7A1.75 1.75 0 0 1 7.25 11");
}

.o4nflab0t {
  d: path("m9.716 10.535l6.894-5.786a1.75 1.75 0 0 1 2.466.216a1.75 1.75 0 0 1-.216 2.466l-6.895 5.785A1.75 1.75 0 0 1 9.5 13a1.75 1.75 0 0 1 .216-2.465m2.106-1.768l2.25 2.681m.814-5.252l2.25 2.681");
}

</style>
