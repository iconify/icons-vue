<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w-xk2kbcn"/><path class="d-2gdibce"/><path class="llzzoib2n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:defibrillator" /></template>
<style>
.d-2gdibce {
  d: path("M12 17.5s-4.5-2.75-4.5-5.75C7.5 10.25 8.6 9 10 9c.9 0 1.6.5 2 1.25C12.4 9.5 13.1 9 14 9c1.4 0 2.5 1.25 2.5 2.75c0 3-4.5 5.75-4.5 5.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.llzzoib2n {
  d: path("M12.75 10.75L11 13.25h2l-1.75 2.5");
}

.w-xk2kbcn {
  d: path("M8.25 4.5h7.5A5.25 5.25 0 0 1 21 9.75v5.5a5.25 5.25 0 0 1-5.25 5.25h-7.5A5.25 5.25 0 0 1 3 15.25v-5.5A5.25 5.25 0 0 1 8.25 4.5m.75 0v-2h6v2");
}

</style>
