<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m2zwvqj6h"/><path class="vmqgp6boi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cyber-hygiene" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m2zwvqj6h {
  d: path("M13.765 20.263q-.61.237-1.265.237h-6q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T3 17v-3.5q0-.172.017-.343t.05-.34q.034-.168.084-.333t.115-.323q.066-.159.147-.311t.177-.294t.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05T6.5 10h6q.247 0 .492.035t.483.103q.237.069.463.171q.225.101.434.234q.209.132.397.292q.189.161.352.346q.164.185.301.392q.136.206.242.43M6 10V7a3.5 3.5 0 0 1 7 0v3m-3.5 3.75v2.75");
}

.vmqgp6boi {
  d: path("M18 13.5q0 4 4 4q-4 0-4 4q0-4-4-4q4 0 4-4");
}

</style>
