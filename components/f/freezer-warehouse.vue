<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="siljrfmyx"/><path class="e3grvl8la"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:freezer-warehouse" /></template>
<style>
.e3grvl8la {
  d: path("M8 21v-6.5h8V21m-8-3.25h8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.siljrfmyx {
  d: path("M2.5 19.25v-4.499a1.75 1.75 0 0 1 1.184-1.656l7.75-2.651a1.75 1.75 0 0 1 1.132 0l7.75 2.651a1.75 1.75 0 0 1 1.184 1.656v4.499A1.75 1.75 0 0 1 19.75 21H4.25a1.75 1.75 0 0 1-1.75-1.75M12 2.5v5M9.75 3.75l4.5 2.5m-4.5 0l4.5-2.5");
}

</style>
