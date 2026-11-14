<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m93dn5bht"/><path class="ielz54hor"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:checkride" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ielz54hor {
  d: path("M9.25 2.5h2.5A1.25 1.25 0 0 1 13 3.75A1.25 1.25 0 0 1 11.75 5h-2.5A1.25 1.25 0 0 1 8 3.75A1.25 1.25 0 0 1 9.25 2.5M5.5 9L7 10.5L9.5 8m-4 6.25l1.5 1.5l2.5-2.5m2.5-4h3.25M12 14.5h3.25M5.5 18.75H12m6.5-4.25v7m-3-2.5l3-2.25l3 2.25M17 21.5h3");
}

.m93dn5bht {
  d: path("M14.215 21.5H6q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T2.5 18V7.5q0-.172.017-.343t.05-.34t.084-.333t.115-.323q.066-.159.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05Q5.828 4 6 4h8.5q.172 0 .343.017t.34.05q.168.034.333.084t.323.115q.159.066.311.147t.294.177t.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333q.033.169.05.34T18 7.5v4.242");
}

</style>
