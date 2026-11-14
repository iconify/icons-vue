<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jtm1d9j8w"/><path class="hh82i4b7w"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bus-delayed" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.hh82i4b7w {
  d: path("M4 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m8.05-1.76q-.118.064-.227.143t-.206.173q-.098.093-.182.198t-.153.221t-.121.24q-.053.124-.089.253q-.036.13-.054.264q-.018.133-.018.268q0 .162.026.322t.078.313t.127.297t.173.273t.214.241t.251.204t.28.16q.147.069.303.113M14.75 18a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jtm1d9j8w {
  d: path("M12.015 17H6q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T2.5 13.5V7q0-.172.017-.343t.05-.34t.084-.333t.115-.323q.066-.159.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05T6 3.5h11q.172 0 .343.017t.34.05q.168.034.333.084t.323.115t.311.147t.294.177q.143.095.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333q.033.169.05.34T20.5 7v5.442M2.5 9h18");
}

</style>
