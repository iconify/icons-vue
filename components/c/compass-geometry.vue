<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="w-rip4ezp"/><path class="li4ugbc3a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:compass-geometry" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.li4ugbc3a {
  d: path("M12 3.5v-.75M11 7L7 17m6-10l4 10M7 19.5a6 3 0 0 0 10 0");
}

.w-rip4ezp {
  cx: 12px;
  cy: 5.25px;
  r: 1.75px;
}

</style>
