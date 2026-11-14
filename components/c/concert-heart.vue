<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jey4w3qun"/><path class="xqzllvbgv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:concert-heart" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jey4w3qun {
  d: path("M3 5.5h18V10a2 2 0 0 0 0 4v4.5H3V14a2 2 0 0 0 0-4Z");
}

.xqzllvbgv {
  d: path("M12 15.75s-4-2.5-4-5.25c0-1.25 1-2.25 2.25-2.25c.75 0 1.25.5 1.75 1c.5-.5 1-1 1.75-1c1.25 0 2.25 1 2.25 2.25c0 2.75-4 5.25-4 5.25");
}

</style>
