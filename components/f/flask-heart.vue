<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y-kz4tb1i"/><path class="zkde5gb9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flask-heart" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y-kz4tb1i {
  d: path("M9.5 2.5v6l-5.75 11Q3 21 4.75 21h14.5q1.75 0 1-1.5l-5.75-11v-6M8 2.5h8");
}

.zkde5gb9h {
  d: path("M12 18.25C9 16 9.25 13 10.75 13c.75 0 1.25.75 1.25 1.25c0-.5.5-1.25 1.25-1.25c1.5 0 1.75 3-1.25 5.25");
}

</style>
