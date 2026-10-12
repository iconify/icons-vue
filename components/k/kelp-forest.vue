<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r40swgbha"/><path class="aculnbs0s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kelp-forest" /></template>
<style>
.aculnbs0s {
  d: path("M6.5 17q2.2-.13 3.4-2q-2.2.13-3.4 2m0-5.5q-1.2-1.87-3.4-2q1.2 1.87 3.4 2m0-4q2.2-.13 3.4-2q-2.2.13-3.4 2m11 10q2.2-.13 3.4-2q-2.2.13-3.4 2m0-5q-1.2-1.87-3.4-2q1.2 1.87 3.4 2m-5.5 5q2.2-.13 3.4-2q-2.2.13-3.4 2m0-5.5q-1.2-1.87-3.4-2q1.2 1.87 3.4 2m-9.25 9.25h18.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r40swgbha {
  d: path("M6.5 20.5c-.75-3 .75-5.5 0-8.5s.75-4 0-6.5m11 15c.75-3-.75-5.5 0-8.5s-.75-1.75 0-3M12 20.5c-.75-3.5.75-6.5 0-10s.75-4.5 0-7.25");
}

</style>
