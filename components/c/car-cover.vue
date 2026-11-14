<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="teczzebqw"/><path class="yzwibxb7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:car-cover" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.teczzebqw {
  d: path("M2.5 16c.5-4 2-5.75 5-6.25c1.5-3.5 3.5-4.5 6-4.5c3 0 4.5 2.5 5.5 5c1.75.5 2.5 2.5 2.5 5.75ZM5 16a2 2 0 0 0 4 0m6 0a2 2 0 0 0 4 0");
}

.yzwibxb7e {
  d: path("M12 16q-.75-3.25 1-6.25");
}

</style>
