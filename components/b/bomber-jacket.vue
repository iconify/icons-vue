<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mjumdiw1y"/><path class="y08mj6bui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bomber-jacket" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mjumdiw1y {
  d: path("M9 3L5 4.5C3.75 5 3 6 3 7.5V19h3.5l1-8v10h9V11l1 8H21V7.5c0-1.5-.75-2.5-2-3L15 3");
}

.y08mj6bui {
  d: path("M9 3q3 3.5 6 0m-3 1.75V21m-4.5-2.5h9M3 17h3.75m10.5 0H21");
}

</style>
