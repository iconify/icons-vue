<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lhe62-b5n"/><path class="gc9twdfab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gift-bag" /></template>
<style>
.gc9twdfab {
  d: path("M12 14c-1.5-2.5-3.5-2.25-3.25-1C9 14 10.5 14 12 14m0 0c1.5-2.5 3.5-2.25 3.25-1c-.25 1-1.75 1-3.25 1m-1.5 3.5L12 14l1.5 3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lhe62-b5n {
  d: path("M5 8h14l-.75 11a2 2 0 0 1-2 2h-8.5a2 2 0 0 1-2-2Zm3.5 0V6.5a3.5 3.5 0 0 1 7 0V8");
}

</style>
