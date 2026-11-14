<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="khrb7na_d"/><path class="k6w90abia"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chat-nurse" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k6w90abia {
  d: path("M7.5 12.75L8.75 6.5h6.5l1.25 6.25c-3-1-6-1-9 0m4.5-5v2.5M10.75 9h2.5");
}

.khrb7na_d {
  d: path("M4 5.5C4 4.1 5.1 3 6.5 3h11C18.9 3 20 4.1 20 5.5v9c0 1.4-1.1 2.5-2.5 2.5H10l-4.5 3.75v-4C4.6 16.5 4 15.6 4 14.5Z");
}

</style>
