<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="of7frgbiz"/><path class="jrijtyq9r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crop-protection" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jrijtyq9r {
  d: path("M12 12.5c0-2.5-1.75-3.75-3.5-3.75C8.5 11 10 12.5 12 12.5m0-1c0-2.5 1.75-3.75 3.5-3.75C15.5 10 14 11.5 12 11.5");
}

.of7frgbiz {
  d: path("m12 2.5l7.5 3V11c0 5-3.5 8.75-7.5 10.5C8 19.75 4.5 16 4.5 11V5.5Zm0 14v-6");
}

</style>
