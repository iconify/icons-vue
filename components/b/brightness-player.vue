<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q55i--bik"/><path class="jhpikgb7t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:brightness-player" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jhpikgb7t {
  d: path("M9.5 8za1.474 1.474 0 0 1 0 2.5a1.307 1.307 0 0 1-2-1.108v-.284A1.307 1.307 0 0 1 9.5 8m6.5 9.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m1.5-3.5v-1m0 8v1M14 17.5h-1m8 0h1M15 15l-.75-.75M20 20l.75.75M20 15l.75-.75M15 20l-.75.75");
}

.q55i--bik {
  d: path("M11.515 15H6q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T2.5 11.5V7q0-.172.017-.343t.05-.34t.084-.333t.115-.323q.066-.159.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05T6 3.5h6q.172 0 .343.017t.34.05q.168.034.333.084t.323.115q.159.066.311.147t.294.177q.143.095.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333t.05.34T15.5 7v4.042");
}

</style>
