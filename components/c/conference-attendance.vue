<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ewi34-80q"/><path class="acnwyccdz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:conference-attendance" /></template>
<style>
.acnwyccdz {
  d: path("m9.971 8.366l2.529.759a.637.637 0 0 1-.163 1.247l-2.813.088A1.012 1.012 0 0 1 8.5 9.25a1.16 1.16 0 0 1 1.471-.884");
}

.ewi34-80q {
  d: path("M3 5.5h18V10a2 2 0 0 0 0 4v4.5H3V14a2 2 0 0 0 0-4ZM7 16l1.75-8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
