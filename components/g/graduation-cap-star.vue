<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xnd-_t-vt"/><path class="suxx-db8r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:graduation-cap-star" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.suxx-db8r {
  d: path("M6.5 11.75v4.5C6.5 18 9 19.5 12 19.5s5.5-1.5 5.5-3.25v-4.5m2.75-1.5v4.5");
}

.xnd-_t-vt {
  d: path("m12.89 5.21l7.47 3.83q.89.46 0 .92l-7.47 3.83q-.89.46-1.78 0L3.64 9.96q-.89-.46 0-.92l7.47-3.83q.89-.46 1.78 0");
}

</style>
