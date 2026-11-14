<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jvzmob5lu"/><path class="tl13t1q5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:house-alert" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jvzmob5lu {
  d: path("M15.345 20H7.5q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311q-.065-.158-.115-.323t-.084-.333q-.033-.169-.05-.34T4 16.5v-4.412q0-.374.079-.74t.234-.706q.154-.341.377-.641q.223-.301.505-.547l4.5-3.937q.118-.104.246-.196q.127-.093.262-.174t.277-.149t.289-.123t.299-.098t.306-.07t.312-.042t.314-.014t.314.014t.312.042t.306.07t.299.098t.289.123q.142.069.277.149q.135.081.262.174q.128.092.246.196l4.5 3.937q.282.246.505.547q.223.3.377.641q.155.34.234.706t.079.74v.725");
}

.tl13t1q5l {
  d: path("M9.5 20v-4a2.5 2.5 0 0 1 5 0v4m3.5-5.25v3.5M18 21h.01");
}

</style>
