<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tses45byc"/><path class="lvnfey3xw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:carbon-calculator" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lvnfey3xw {
  d: path("M7.5 5.5h4A1.5 1.5 0 0 1 13 7a1.5 1.5 0 0 1-1.5 1.5h-4A1.5 1.5 0 0 1 6 7a1.5 1.5 0 0 1 1.5-1.5M6 12h.01m3.49 0h.01M13 12h.01M6 15h.01m3.49 0h.01M6 18h.01m3.49 0h.01m5.74 3H20a1.75 1.75 0 0 0 0-3.5a2.75 2.75 0 0 0-5.25.25a1.75 1.75 0 0 0 .5 3.25");
}

.tses45byc {
  d: path("M11.515 21.5H6.5q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T3 18V6q0-.172.017-.343t.05-.34t.084-.333t.115-.323q.066-.159.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05T6.5 2.5h6q.172 0 .343.017t.34.05q.168.034.333.084t.323.115q.159.066.311.147t.294.177t.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333t.05.34T16 6v7.042");
}

</style>
