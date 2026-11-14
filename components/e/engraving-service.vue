<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zoodtsmia"/><path class="v2rsat17o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:engraving-service" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v2rsat17o {
  d: path("M5.5 13C7 9 8.75 9 8.75 11.5s1.5 2.5 2.5.5s2.5-2 2.5 0c0 1.5 1.5 1.5 2.75.25m-2.125 8.25l.072-.717a1.5 1.5 0 0 1 .432-.912l3.81-3.81a1.5 1.5 0 0 1 2.122 0l.128.128a1.5 1.5 0 0 1 0 2.122l-3.81 3.81a1.5 1.5 0 0 1-.912.432l-.717.072a1.028 1.028 0 0 1-1.125-1.125M17.75 16L20 18.25");
}

.zoodtsmia {
  d: path("M11.915 18.5H6q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T2.5 15V8q0-.172.017-.343t.05-.34t.084-.333t.115-.323q.066-.159.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05Q5.828 4.5 6 4.5h12q.172 0 .343.017t.34.05q.168.034.333.084t.323.115t.311.147t.294.177q.143.095.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333q.033.169.05.34T21.5 8v4.142M5 7h.01M19 7h.01M5 16h.01");
}

</style>
