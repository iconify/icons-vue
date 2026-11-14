<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0ak7iy9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:firewall-server" /></template>
<style>
.t0ak7iy9t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 2.5h7.5A3.5 3.5 0 0 1 17 6a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 6A3.5 3.5 0 0 1 6 2.5m6.015 16.75H6q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T2.5 15.75t.017-.343t.05-.34q.034-.168.084-.333t.115-.323q.066-.159.147-.311t.177-.294t.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05T6 12.25h7.5q.593 0 1.153.195M6 6h.01M6 15.75h.01M18 21.5c-2 0-3.25-1.5-3.25-3.25c0-2 1.75-2.75 2.5-4.75c.75 1 1.25 2 1.25 3q1.125-.75 1.5-1.5c.75 1 1.25 2 1.25 3.25C21.25 20 20 21.5 18 21.5");
}

</style>
